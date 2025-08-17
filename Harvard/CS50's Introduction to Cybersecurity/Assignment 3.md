# Assignment 3

---

**Q1: Via what technique(s) might a malicious actor "crack" software (that is, bypass registration/payment to use it)?**
**A1:** Binary patching, keygens, memory hooks, DLL injection, fake license services.

---

**Q2: Distinguish the nature of two types of "cross-site" attacks we discussed: cross-site scripting (XSS) and cross-site request forgeries (CSRF).**
**A2:**

* **XSS:** Runs injected JavaScript in the victim’s browser.
* **CSRF:** Forges authenticated requests without requiring JavaScript injection.

---

**Q3: Why do we need to escape certain characters in inputs?**
**A3:** To convert control characters into literals, preventing injection attacks.

---

**Q4: In the context of SQL, what is a prepared statement?**
**A4:** 

---

**Q5: Why is client-side validation considered "less secure" than server-side validation?**
**A5:** Client-side code can be tampered with or bypassed, while server-side checks cannot be skipped.

---

**Q6: Even if many users treat open-source software casually, why might it still be a good thing to use (or develop) more open-source software, from a security perspective?**
**A6:** Open-source allows “many eyes” to review code, leading to faster patches and greater assurance that no hidden backdoors exist.

---

**Q7: How are package managers similar to app stores (such as Apple’s App Store, Google Play, Microsoft Store, etc.), from a cybersecurity perspective?**
**A7:** Both rely on cryptographic signing. They only accept software signed by authorized developers, ensuring users install trusted, verified code.

---

**Q8: What threat does use of Content-Security-Policy (CSP) fields in our source code help to defend against?**
**A8:** CSP restricts permitted sources of content, mitigating XSS and other injection-based attacks.

---

**Q9: Provide a specific example of a situation when you might want to use the HTTP POST method instead of the HTTP GET method.**
**A9:** For login forms or other sensitive submissions. POST prevents credentials or sensitive data from appearing in the URL or browser cache.

---

**Q10: Why was Heartbleed such a threat to a user's security?**
**A10:** 

---