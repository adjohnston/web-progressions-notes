#Web Authentication: a Future Without Passwords?
## Natasha Rooney - GSMA

Passwords are kinda crud

---

- hard to remember
- phishable - tell me your password for a free pen
- rely on trust

---

781 data breaches in 2015 - 170m records stolen - avg $3.8m per breach

---

### Some ways to help
We tried…

- one time passcodes
- password aggregators
- 2 factor auth (sms hacking)

---

###Security or Usability?

FIDO alliance

- authentication standards
- do not sacrifice usability
- privacy by design

Has two frameworks UAF & U2F

UAF - same user as before? biometric or otherwise
U2F - is a user present? same as before? prove you have something (dongle/device, GAuth?)

Kinda cool because…
- deploy once for all "authenticators"
- no server has your fingerprint (or other biometric)
- usability
- PKI stronger than user/pw

---

- public key cryptography (PKC)
- symmetric crypto (Caesar cypher)
- asymmetric crypto (2 keys) 1 secret key and 1 public key
- certs (anyone can be a certificate authority CA)
- SSL/TLS

---

###What Does it have to do with the Web?

WebAuth WG 

- Web Authentication API  - requesting asymmetric key pair, spec is being edited now, all can change
