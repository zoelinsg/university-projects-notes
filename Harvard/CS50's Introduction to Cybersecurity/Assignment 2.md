# Assignment 2

---

**Q1: Considering its nature, what type of cybersecurity threat might pose the most unique risk to research projects like SETI\@Home? How might such a threat be realized?**
**A1:** Supply chain compromise. If the project’s main server is breached, attackers could push malicious work units or updates; volunteers’ clients would then execute the code, creating botnets or installing malware.

---

**Q2: What is a zero-day attack, and why are such attacks a threat?**
**A2:** Zero-day exploits target vulnerabilities unknown to the vendor. Since no patch is available, targets cannot defend themselves, making these attacks especially dangerous.

---

**Q3: What is port scanning and how does it pose a threat?**
**A3:** Port scanning probes many TCP/UDP ports on a host to find open services. Attackers use this map to select and exploit vulnerable services.

---

**Q4: What is a supercookie? How do we typically acquire/receive them, and how might they threaten our systems?**
**A4:** A supercookie is a resilient tracker that regenerates even after deletion. They’re often injected via HTTP headers by websites or ISPs. They enable persistent tracking and may facilitate session hijacking.

---

**Q5: How do worms differ from viruses?**
**A5:** Worms self-replicate and spread autonomously over networks. Viruses attach to host files/programs and typically spread only when the host is executed.

---

**Q6: Provide an example of a technique that implements “security through obscurity.”**
**A6:** Running SSH on a non-standard port instead of port 22.

---

**Q7: Distinguish between SSH and VPN.**
**A7:**

* **VPN:** Creates an encrypted tunnel between two points, securing all traffic.
* **SSH:** A secure protocol to execute commands on a remote server or transfer data over an encrypted channel.

---

**Q8: What is the purpose of the X.509 standard?**
**A8:** X.509 defines the format of public key certificates in PKI. It underpins SSL/TLS, S/MIME, code signing, and binding identities to public keys.

---

**Q9: Why might companies conduct penetration tests?**
**A9:** To find vulnerabilities before criminals do, validate security controls, meet compliance/customer requirements, and reduce breach risks and costs.

---

**Q10: Which HTTP status code is most likely to indicate that a Distributed Denial of Service (DDoS) attack is underway?**
**A10:** 503 Service Unavailable
