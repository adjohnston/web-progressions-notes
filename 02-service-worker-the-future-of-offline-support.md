# Service Worker, the Future of Offline Support
## Jungkee Song - Samsung

Samsung browser 4.0 includes service workers

---

Service workers bring reliability, are first class and allow for engaging experiences
- fast loading, works on flaky networks
- allow the user to download content they want for offline
- do what native does
- home screen access, push notifications

---

### Problems
What service workers are trying to solve
 
- offline and "lie-fi" 
- a background service was not possible without a page (push notifications, alarm API)

---

### Concepts
What a service worker is

- a programable proxy, sits between the page and the network
- just a script that runs in the background `const worker = new Worker('some-worker.js')`
- responds to events
- intentionally short lived, lifetime is bound to the page
- HTTPS is required (can do powerful things, needs to make sure it hasn't been tampered with during it's own fetch)
- can be updated, after 24 hours will call to network to update
