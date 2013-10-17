
# Portfolio
The following is a small list of projects I developed.

===============
### Teletracker
<img alt="" width="96px" src="https://lh3.ggpht.com/GMaKmV3XXr5y_mHor3BNSvfeaURg7NCSHmzAR3rlXsxOVyGfyFLK55NT0wI=w300-rw" />

People loose their phones all the time. Often by theft.

Imagine if each time a phone was sold the the buyer would pay an extra $5 - $10 for the sales rep to install a piece of tracking software. I would like that software to be mine.

The challenge with a project like this is that unless you are an OEM or the phone is rooted you can eliminate the app by doing a factory reset.

When Samsung launched a similar project I discontinued the development because I felt it would be impossible to compete. Later on, Google also launched Device Manager. However both of these projects are still less featurefull and neither can handle a factory reset.


#### Features
* Locate phone
* Hide/unhide app from app drawer
* Various message commands
* Simcard verifier
* More.


**Keywords**: RubyOnRails, REST, Postgresql, Android, GCM, Javascript, Google Maps, Sass, HAML and more.

<img alt="" width="200px" src="images/teletracker_devices.png" />|
<img alt="" width="200px" src="images/teletracker_locate.png" />|
<img alt="" width="200px" src="images/teletracker_info.png" />


==============
### SMS Wakeup
<img alt="" width="96px" src="https://lh3.ggpht.com/6GGfhBQ6kYmA3Pm8Fs10WZ1yZaXMoMvCAMqaQDkdagzrxgOMCJuy9jS3_RsNxYX7hQU=w300-rw" />

Small app designed to aid the heavy sleeper getting out of bed.


**Keywords**: SMS Broadcast Receiver, Custom Content Provider, Sqlite, CursorLoader

<img alt="" width="200px" src="https://lh5.ggpht.com/0jrPS5iEo2jRFJO7XRiPxA-NIdS-En7UDDF0vLTMaZ9nNlyLTy-ISsDmEDq1u4aiAe4=h900-rw" />|
<img alt="" width="200px" src="https://lh4.ggpht.com/VcaSob-KV6qKiPrJ9nBSHgalneozeoo8FBw-McbqAfldnZeANmeYtON5_ALLboQTUyE=h900-rw" />|
<img alt="" width="200px" src="https://lh3.ggpht.com/WRMlzy58pCAtLpBEbW-XxUl2gceoHaUHV3cUkPggBJ_62AWyARCtlNEmPc4PE2rTk5Yq=h900-rw" />

**Play**: https://play.google.com/store/apps/details?id=com.snot.smswakeup

**Github**: https://github.com/snot/SMS-Wakeup


==================
### Where Are You?
<img alt="" width="96px" src="https://lh6.ggpht.com/8JPOJucOGC8S7QqhK1Ea9kKDTqldmacTHqW8bM0bqzEFtseSmczTVK8Svf_jZNna8A=w300-rw" />

More people than you should think are unable to share their own location with others. This app takes the reverse approach and let you request the location of someone else. It does so by sending an SMS containing a link for the receiver to click. When the user clicks the link it is taken to a website which requests the location using Javascript and submits the location to a server which sends it back to the app.


**Keywords**: Contact Provider, Custom Content Provider, CursorLoader, Google maps, AppEngine, GCM, Javascript, AJAX

<img alt="" width="200px" src="https://lh5.ggpht.com/PIK8AaIZsCOt-E3eAhQCZpRjTpd0SiGeEPY5Qd9CnhRL0LXIrFh-nxbfZvnyQOU4mhE=h900-rw" />|
<img alt="" width="200px" src="https://lh5.ggpht.com/jUY5aiPRvOVN6PXYnILANRQbP8pzcTtS-yd2tKOfNSt_VxYxDgQhoebfEqzVnu1FFks=h900-rw" />|
<img alt="" width="200px" src="https://lh5.ggpht.com/MLITNAUi66fRFMT-RTeBX5yzUla8Axz-Q9mZvhblyP5EWEUElbzO162pKYJewVTqnDE=h900-rw" />|
<img alt="" width="200px" src="https://lh5.ggpht.com/89VtejB-3-0ZBi60pBlaaxYvMiuA3w_CohXWijTCghMCsPSc-09VoN8oCMjJsaVAxQ=h900-rw" />

**Play**: https://play.google.com/store/apps/details?id=com.snot.whereareyou

**Github**: https://github.com/snot/WhereAreYouApp

<!--
======================
### Where Are You? GAE
The backend for my "Where Are You?" app described above.

**Keywords**: AppEngine, GCM, Javascript, AJAX
-->


=====================
### Bloatware Remover
<img alt="" width="96px" src="https://lh4.ggpht.com/FyCGWunnTDzW3N3-03sv0gKCrs8wblzIjfwiTT2nO3tuJ9V5R6oOW-ee7ha16jA0sOg=h180" />

This app lets you remove or freeze system apps.

**Keywords**: PackageManager, Root, AsyncTaskLoader

<img alt="" width="200px" src="https://lh5.ggpht.com/XzvSVAt2LS-yxusdSE8auF25tmOJf2yIsv-w1ccCtLL7mKcAVBlb9mcnxs_JnXuP00g4=h900-rw" />|
<img alt="" width="200px" src="https://lh6.ggpht.com/f8p8M9eWMWZC0sCOIrke5-yYWmku9pff0frIQ4XRGRcMhtebu0SniFTiXrJ8zmMoKA=h900-rw" />|
<img alt="" width="200px" src="https://lh4.ggpht.com/niB2BW33Enr_eQKd_L3RIv7lUVWz6oqccyydMAbE3tuBetyjSxBzBIT4ebeCqEZfCOg=h900-rw" />


==================
### Danish Live TV
<img alt="" src="images/danish_live_tv_logo.png" />

Perhaps the simplest pice of software that I've ever written but still the most successful and widely used.

By wrapping links to live streaming of danish public services channels in a listview and presenting that as the sole content of an app I got more than 60000 downloads and more then 21000 active users. At one point I was in the top five of most downloaded apps in the danish app store.

However this apps life was short lived and abruptly ended by the laywers representing DR. I made it as a hobby project. I said they could have it. With source code and all.  DR still hasn't made their own app.


<img alt="" width="200px" src="https://lh3.ggpht.com/qnATxTXzfwnJB_oG-jUHf9tIRlI0KgtU8rek2vY_1FQZb7XFWn_xznUh8pGwkY-lvUs=h900-rw" />|
<img alt="" width="200px" src="https://lh6.ggpht.com/PlwAQI-B9quqRDNxANPnPB1GAaqB1xRgQqPYD6IUoTywMw6mlLibuU8GiFJv74bOxW8=h900-rw" />|
<img alt="" width="400px" src="https://lh3.ggpht.com/WnqsZVGs1kEZBamEZzov8sUsR-_qtpbyEoqSlXg0l-Euh8VG_M-_Ahk7M_Ftz43y1fw=h900-rw" />

