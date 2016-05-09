#Moving to HTTPS with Lets Encrypt
## Soledad Penadés - Mozilla

###Securing Transmissions
HTTP + TLS = HTTPS, an encrypted connection between browser and server.

With encryption…
  - privacy
  - data integrtity
  
Attacks against insecure connections
  - inserting ads
  - replace existing ads with their own
  - non-ethical behaviorual tracking
  - stealing user credentials
  
HTTPS
  - safer by design
  - show empathy with your users
  - newer, privacy sensitive JS APIs will only work over HTTPS
  - HTTP2
  
---

###HTTPS in Practice

The chain of truth for certificates. Search up until you find a legitmate source of the certificate. If none can be found it will show a unsafe notification.

---

###Let's Encrypt
  - install their client in your server
  - get new digital certificate for using their client
  - start using keys from cert
  - automatice renewal
  
Let's Encrypt are a new certificate authority. It is free, community project steered by the ISRG.

---

###Under the Hood
- the client contacts the server
- files are placed in the webroot dir
- the server reads and validates
- if all ok a certificate is issues and you get keys for the domain

---

###Basic HTTPS can be vulnerable
  - older protocols (SSL) use only TLS
  - older clients may not work
  - older ciphers (some have been broken)
  
Mozilla SSL generator

####Client Level Security
- enable strict transport security
- after initial HTTPS visit, browser will demand HTTPS

SSL Labs for testing encryption on the domain

---

###Old New HTTPS only APIs
- webcam
- geolocation
- appcache

And in the future?

- Background sync
- bluetooth
