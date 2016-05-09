# Progressive Webapps and the Future of the Web
## Bruce Lawson

Make the web better for… 
 - developers
 - consumers
 - the next 4 billion people without web (yet)
 
In 2004 browsers were scared of flash and silverlight. HTML5 was the competitor to those in 2009.

2016 a new threat - apps of doom.

HTML5 there's an API for that
- canvas
- video
- geolocation
- etc

2014 - 14% spent on web vs apps mobile

Consumers want UX
UX is a feature too

---

### Progressive Web Apps
- "install" to the home screen
- have their own icon (defined by the web developer)
- can launch full-screen, portrait or landscape
- but "live" on the Web 

(full back to a "website" when these things can't be done)

- A typical webapp is 20mb which takes over 30 mins via 2G
- Phones are used for very personal things

---

### Manifest
A manifest file (json) lives in the <head />

- has an icon
- a name
- start full-screen
- etc

Manifest Validator - http://manifest-validator.appspot.com
Works best with HTTPS
Chrome/Opera suggest adding to homescreen with manifest

---

AppCache = SlapDache
Appcache is a douchebag article by Jake Archibald

---

### Service Worker
- Push notifications
- Background sync

---

Why are standards slow? To compete against native we need to move faster. 

Extensible Web Manifesto - future of standards

"The Javascriptification of the Web"

It's been done before with the <picture /> element

WICG

---

### Extending CSS = Houdini
- Parser API (before you could never see the parser and what it was doing)
- Font Metrics API
- Custom Layout
- Custom Paint
- Composited Scrolling
