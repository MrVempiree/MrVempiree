<!-- PROFILE HEADER -->

<h1 align="center">⚡ Lavish Gangwar | Mr Vempire</h1>

<h3 align="center">
  🛡️ Aspiring Security Engineer • Web Application Security • Penetration Testing
</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Web%20Security-red?style=for-the-badge&logo=owasp&logoColor=white" />
  <img src="https://img.shields.io/badge/Domain-Cybersecurity-black?style=for-the-badge&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Mindset-Security%20First-blue?style=for-the-badge&logo=hackthebox&logoColor=white" />
</p>

> **Building and learning since December 2024.** This GitHub account was created in
> May 2026, so the public commit history here is shorter than the work actually is.
> I would rather be precise about that than backfill a timeline.

---

## 👨‍💻 About Me

Hey! I'm **Lavish Gangwar**, also known as **Mr Vempire**.

I'm passionate about cybersecurity, web application security,
vulnerability assessment, and penetration testing.

My focus is on understanding how applications work, identifying
security weaknesses, learning practical testing methodologies,
and helping make systems more secure.

🔎 **My security interests include:**
- Web Application Security
- OWASP Top 10 Vulnerabilities
- Authentication & Authorization Testing
- API Security
- Vulnerability Research
- Security Automation
- Ethical Hacking

🧠 I believe in a security-first mindset, continuous learning,
responsible disclosure, and practical problem-solving.

📍 **Location:** Bareilly, Uttar Pradesh, India
🌐 **Work Preference:** Remote / Hybrid
💼 **Availability:** Open to suitable cybersecurity opportunities

---

## 🛡️ Core Security Skills

| Area | Skills |
|---|---|
| Web Security | OWASP Top 10, XSS, SQL Injection |
| Security Testing | Vulnerability Assessment, Manual Testing |
| Web Tools | Burp Suite, Nmap |
| Networking | TCP/IP, DNS, HTTP, HTTPS, Ports |
| Operating Systems | Linux, Kali Linux |
| Programming | Python, SQL, TypeScript |
| Web Development | JavaScript — Learning |
| Version Control | Git & GitHub |
| Security Concepts | Authentication, Authorization, Access Control |

---

## ⚙️ Technical Toolkit

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,js,linux,bash,git,github,mysql,typescript" />
</p>

### 🔧 Security Tools

<p align="left">
  <img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white" />
  <img src="https://img.shields.io/badge/Nmap-214478?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white" />
</p>

---

## 🧪 Selected Work

I would rather show you code you can clone, run, and break than list
credentials. Each project below is real, runs locally, and is covered by tests.

### [`web-security-labs`](https://github.com/MrVempiree/web-security-labs) — XSS, SQL injection, broken access control

Reproducible web application security labs. Each lab pairs a **working vulnerable
implementation** with a **remediated one**, and a test suite that proves the two
behave differently.

| Lab | Vulnerability | What it demonstrates |
|-----|---------------|----------------------|
| `xss` | CWE-79 | Context-aware output encoding, and why HTML-encoding is the wrong fix for a JavaScript string context |
| `sqli` | CWE-89 | Why parameterised queries work *structurally* rather than by filtering input |
| `brokenAccessControl` | CWE-639 | Authenticating is not authorising — and the 401 vs 403 distinction |

- **65 automated tests, all passing** (`node --test`, no install step).
- **Zero runtime dependencies** — nothing to audit but the code you came to read.
- TypeScript runs natively on Node 22.6+, so there is no build step and no `node_modules`.
- **Safety is enforced, not documented:** the server binds to `127.0.0.1` by default and
  *refuses* a non-loopback bind unless `ALLOW_NON_LOOPBACK_BIND=1` is set explicitly.
  That refusal is covered by its own test file.
- Includes `README.md`, `SECURITY.md`, `CONTRIBUTING.md`, `LICENSE`, and a CI workflow.

**Try it locally:**

```bash
git clone https://github.com/MrVempiree/web-security-labs.git
cd web-security-labs
npm test          # 65 tests
npm start         # http://127.0.0.1:8080
```

Each lab states plainly what it does **not** model — no real database, no browser, no
stored or DOM-based XSS — rather than implying coverage it does not have.

---

## 📂 Other Repositories

Explore my repositories to follow my learning journey,
technical experiments, and cybersecurity development.

- 🔹 **XXS-AUTOMATION** — Security automation project.
- 🔹 **ValnScanner** — Vulnerability-scanning project.

More projects and documentation will be added as they develop.

---

## 🎯 Areas of Interest

- 🔍 Web Application Penetration Testing
- 🛡️ Vulnerability Assessment
- 🔐 API Security Testing
- 🧪 OWASP Top 10 Security Testing
- 🤖 Security Automation
- 🐍 Python-Based Security Tools
- 📚 Continuous Cybersecurity Learning

---

## 🔒 Security Ethics

Everything in my work follows one rule: **only test what you own or have explicit
written permission to assess.**

- Vulnerable labs bind to `localhost` and are never intended for public deployment.
- No tool I build performs unauthorized scanning, stealth operation, credential
  attack, or automatic exploitation.
- Findings are reported responsibly, with sensitive data redacted.
- Secrets are never committed, logged, or requested in chat.

If you find a vulnerability in something I maintain, please report it privately rather
than opening a public issue.

---

## 💼 Open to Opportunities

I'm interested in opportunities such as:

- Cybersecurity Intern
- Junior Penetration Tester
- Junior Web Security Analyst
- Vulnerability Assessment Intern
- Junior Security Analyst
- Entry-Level Security Engineering Roles

I'm eager to strengthen my practical skills, collaborate with
security professionals, and contribute to meaningful security work.

---

## 📬 Contact Me

<p align="left">
  <a href="mailto:lavishgangwar36@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

📧 **Email:** lavishgangwar36@gmail.com
🌐 **GitHub:** [@MrVempiree](https://github.com/MrVempiree)

---

<p align="center">
  <i>"Think like an attacker. Build like a defender. Learn every day."</i>
</p>

<p align="center">
  🛡️ Security • 🔍 Research • ⚡ Continuous Improvement
</p>
