# cybersecuritytask3
Use free tools to identify common vulnerabilities on your computer.
---

**GitHub Repo Structure Suggestion**

```
vulnerability-scan-task/
├── screenshots/
│   ├── scan-summary.png
│   ├── critical-vulnerability.png
├── report/
│   └── vulnerability-scan-report.pdf
├── README.md
```

---


```markdown
 Basic Vulnerability Scan on My PC

 Task Overview

This project demonstrates how to perform a basic vulnerability scan on a local machine using free tools like **OpenVAS Community Edition** or **Nessus Essentials**.

---

Objective

Use free tools to identify and report common vulnerabilities on a personal computer.

---

Tools Used

- [OpenVAS Community Edition](https://www.greenbone.net/en/community-edition/) *(Free open-source vulnerability scanner)*
- [Nessus Essentials](https://www.tenable.com/products/nessus/nessus-essentials) *(Free for personal use)*

---

Steps Performed

1. Installed Nessus Essentials (can also use OpenVAS).
2. Set up scan target as `localhost` (127.0.0.1).
3. Launched a full vulnerability scan.
4. Waited for the scan to complete (approx. 45 minutes).
5. Reviewed the scan report and analyzed the vulnerabilities.
6. Researched simple fixes and mitigations.
7. Documented the most critical issues found.
8. Took screenshots of important findings.

---

Deliverables

- 📄 [Vulnerability Scan Report](report/vulnerability-scan-report.pdf)
- 🖼️ Screenshots of scan results:
  - Summary report
  - Critical vulnerability details

---

 Notable Vulnerabilities Found

| Vulnerability | Severity | Description | Suggested Fix |
|---------------|----------|-------------|----------------|
| CVE-XXXX-XXXX | Critical | Outdated software version exposes system to remote code execution | Update to latest version |
| CVE-YYYY-YYYY | High     | Unpatched service detected | Apply official patch from vendor |
| Open Ports    | Medium   | Unused ports open to network | Disable unnecessary services |

 Conclusion

The scan helped uncover potential vulnerabilities on my system. Regular scanning and patching are crucial for maintaining a secure system.

