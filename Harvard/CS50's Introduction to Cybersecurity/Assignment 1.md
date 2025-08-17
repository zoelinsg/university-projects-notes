## Assignment 1

**Q1: Characterize the difference between a database hack and a database leak.**

**A1:** 

**Q2: In what sense might files not actually be deleted even if you empty the recycle bin on Windows or empty the trash on macOS?**

**A2:** Emptying the Recycle Bin/Trash only removes file pointers; the actual data stays on disk until overwritten, so it can still be recovered.

**Q3: How do quantum computers differ from traditional (non-quantum) computers?**

**A3:** Quantum computers use qubits (superposition and entanglement) to achieve exponential speedups—potentially cutting the time to break encryption compared to classical machines.

**Q4: What is the term for the prevailing method via which public-key (i.e., asymmetric) cryptography enables two parties to establish a shared secret, even over an insecure (i.e., unencrypted) channel?**

**A4:** Diffie–Hellman key exchange.

**Q5: What is a salt, in the context of this lecture?**

**A5:** A salt is a random value added to a password before hashing so identical passwords yield different hashes, thwarting precomputed attacks.

**Q6: Suppose that Alice and Bob need to coordinate a meeting, as by exchanging emails using Microsoft Outlook, a popular client for email. If their emails are encrypted in-transit, who (besides Alice and Bob, or anyone with access to their computer) might nonetheless be able to read the emails, if anyone?**

**A6:** Email provider and admins.

**Q7: Suppose that you have been hired to perform some work for Charlie. After agreeing to terms, you send the contract to Charlie via email, and, later that day, you receive a digitally signed copy from an email address that appears to belong to Charlie but isn't the one to which you sent the contract originally. How can you be as certain as possible, technologically (that is, without consulting Charlie) that Charlie was the one who digitally signed the contract?**

**A7:** Grab Charlie’s public key and check the signature—if it verifies, you can be sure he’s the one who signed.

**Q8: Suppose that a company has made a large file available for download via its website. Why might they also make available the MD5 hash of that file (as is indeed a common practice)?**

**A8:** Publishing the file’s MD5 hash lets users compute the hash after downloading; a matching value proves the file was neither corrupted nor tampered with during transfer.

**Q9: Identify one or more significant differences between a cipher and a hash.**

**A9:**

* **Cipher:** Uses a key to scramble data and the same (or related) key to get it back—all about privacy.
* **Hash:** One-way math with no key; turns any input into a fixed-size fingerprint so you can spot any change but never reverse it.

**Q10: Otkz D zvmizy v amzz kjdio! di ocz wjs wzgjr. (Not random typing.)**

**A10:** “Type I earned a free point!”