#Day 1 Html5DevCon

Performance is important. For a variety of reasons. Pages are getting heavier and it affects load times (perceived and real) and we need to work with that [take slides from the presentation to cover the difference between gmail and amazon regarding perceived load speed versus windows.onload speed]

Why is this important when you have a captive audience? 

Even though it is a captive audience they'll still turn away from your content. They will just not take the courses and complain that the site is slow to load. This is even more important in a global environment where the highest speed can fluctuate wildly and that can affect the user experience for our end users. 

* http://httparchive.org/ for more statistics regarding we access worldwide
* http://stevesouders.com/docs/html5devconf-howfast-20130401.pptx for the keynore presentation: "How fast is the web"

#Modernizr

Modernizr is a feature detection engine that allows both feature detection and modular development. We can create support tiers depending on the features the browsers support and then work with that tier only (we don't add features that a browser can't support and we code all the features that we need and only those we need)

The objective is not for all the browsers to render content the same way. But to display the content the best way a browser can. 

#Video on the web:

##Full Presentation
* http://www.w3.org/2013/Talks/0401-web-video/

###Imporant Information
* Most of it can be scripted, either directly, via canvas or SVG
* Event demo @ w3c: http://www.w3.org/2010/05/video/mediaevents.html

different formats and patent wars. MP4 is encumbered and recently so it is. 

##Captioning

Has builtin support for captioned tracks and subtitles. There are two formats (go figure): WebVTT (newer W3C recommendation and better support: Chrome, IE, Safari) and TTML (older with a TV heritage)

Issues with: 
* SMPTE-TT (superset of TTML) being a safe harbor
* Differing support for each standard (TTML from Video/broadcast industries and Web vendors supporting WebVTT) 
* FCC rules regarding video content previously delivered via TV (must be captioned)
	
##Full Screen Display

Web video allows full screen display
https://dvcs.w3.org/hg/fullscreen/raw-file/tip/Overview.html

##Accessibility:
http://www.w3.org/WAI/PF/media-a11y-reqs/
* type of disability
* Alternative accommodations
* System requirements (accessibility technological)
	
##Media Capture APIs
http://dev.w3.org/2009/dap/camera/

2 way communication by using the camera API and a video or canvas tag to display the incoming content. 

##Media Source Extensions
https://dvcs.w3.org/hg/html-media/raw-file/tip/media-source/media-source.html

Developer build media stream from a series of video and audio chunks
http://www.w3.org/WAI/PF/media-a11y-reqs/
* Adaptive Streaming
* Ad insertion
* Time shifting
* Video editing

##Encrypted Media Extensions
https://dvcs.w3.org/hg/html-media/raw-file/tip/encrypted-media/encrypted-media.html

Connects CMS to content provider serving encrypted media. DRM?

* How does it related to Canvas, CSS, accessibility?
	
##Real Time Communications
http://www.webrtc.org/

* What video codec? 
* Mozilla and Chrome support the feature but not the same codecs
 
###Client-side latency mesaurements
* https://dvcs.w3.org/hg/webperf/raw-file/tip/specs/NavigationTiming/Overview.html
* http://www.w3.org/TR/resource-timing/
* http://www.igvita.com/2012/04/04/measuring-site-speed-with-navigation-timing/

#Responsive web design -- Take your app offline

* Offline is now possible with HTML5
* Way more than online web applications
* What do we do without Internet connection
** Flying? (I've been asked this about the current LMS @ work)
** Outside cell tower range
* MVC architecture

