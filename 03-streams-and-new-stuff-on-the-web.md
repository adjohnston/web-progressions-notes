# Streams & New Stuff on the Web
## Jake Archibald - Google

Service workers are enhancements
Load content with UI shells

---

###The Web VS Single Page Apps
####Websites
- html starts downloading
- css download
- render
- more rendering as html downloads

####SPAs
- html downloads
- css downloads
- render
- JS downloads
- JS parses & executrs
- JS downloads content
- Content added to page
- render

load time performance is not about sizes, it's about enhancement. show them what you got.

---

### Fetch Streams
`fetch(url).then((res) => res.json())` es6
`const res = await fetch(url)` es7 

####example
```
const res = await fetch('https://html.spec.whatwg.org')
const reader = res.body.getReader()

let result = await reader.read()

if (!result.done) {
  // something
}
```

- you can cancel streams
- to match strings you need to buffer by search term length - 1 i.e. searching horse = 'my lovely h', 'ly h' + 'orse running'

Search the HTML spec for horse and shit - both exist
\#canvasshitregion 

---

**blog post** - 2016 - the year of web streams
