<h1 align="center">Hi 👋, I'm Prem Sharma</h1>

<h3 align="center">
Backend Developer → Application Security Engineer
</h3>

<p align="center">
  <a href="https://github.com/SharmaPrem9567">
    <img src="https://img.shields.io/github/followers/SharmaPrem9567?label=Followers&style=for-the-badge" />
  </a>
  <a href="https://github.com/SharmaPrem9567?tab=repositories">
    <img src="https://img.shields.io/github/repos/SharmaPrem9567?style=for-the-badge&label=Repositories" />
  </a>
  <a href="https://github.com/SharmaPrem9567?tab=stars">
    <img src="https://img.shields.io/github/stars/SharmaPrem9567?affiliations=OWNER&style=for-the-badge&label=Stars" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=SharmaPrem9567&style=for-the-badge&label=Profile+Views" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/prem-appsec">LinkedIn</a> •
  <a href="https://medium.com/@premwork25">Medium</a> •
  <a href="https://github.com/SharmaPrem9567">GitHub</a>
</p>

👨‍💻 About Me
I'm a backend developer moving deeper into Application Security, with a focus on understanding how applications are designed, attacked, secured, and continuously validated.
My focus is on:
- 🔐 Web & API Security
- 🛡️ Application Security & Secure SDLC
- 🔑 Authentication, Authorization & Session Security
- 🎫 JWT Security & Refresh Token Rotation
- 🚨 BOLA / IDOR & Broken Access Control
- 💉 SQL Injection, XSS, SSRF & SSTI
- 🧪 SAST / SCA / DAST
- 🐳 Docker & Container Security
- ⚙️ CI/CD Security
- 🏗️ Threat Modeling with STRIDE
- 🔎 Vulnerability Assessment & Web Pentesting
My advantage: I understand how backend systems are built before looking at how they can be attacked.

🎯 What I Build
Backend Engineering
        ↓
API Design & Architecture
        ↓
Authentication & Authorization
        ↓
Security Controls
        ↓
Offensive Security Testing
        ↓
Remediation & Verification
        ↓
Security Architecture
I build backend APIs with security controls designed into the architecture, then validate those controls through offensive testing and automated security checks.
🚀 Featured Projects
<table>
<tr>
<td width="50%">

<h3 align="center">🔐 SecureDocs</h3>

<p align="center">
  <a href="https://github.com/SharmaPrem9567/SecureDocs">
    <img src="https://img.shields.io/badge/View-Repository-181717?style=for-the-badge&logo=github">
  </a>
</p>

<p>
Secure document management backend built with Node.js, Express, PostgreSQL, Redis and Docker.
</p>

<b>Engineering:</b>
- 20+ REST API endpoints
- Modular controller/service architecture
- PostgreSQL schema design
- Redis cache-aside pattern
- Pagination
- JWT authentication
- Role-based access control
<b>Security:</b>
- Ownership-based authorization
- Refresh-token rotation
- Redis session/revocation store
- Replay-attack detection
- Rate limiting & temporary lockout
- Secure password-reset OTP flow
- Audit logging
- Secure file upload controls
- Helmet, CORS restrictions & HttpOnly cookies
</td>

<td width="50%">

<h3 align="center">🔍 SecureVault</h3>

<p align="center">
  <a href="https://github.com/SharmaPrem9567">
    <img src="https://img.shields.io/badge/View-Assessment-181717?style=for-the-badge&logo=github">
  </a>
</p>

<p>
Security assessment of a locally-run Node.js REST API using automated and manual application-security testing.
</p>

<b>Assessment:</b>
- SAST with Semgrep
- SCA with Snyk & npm audit
- DAST with OWASP ZAP
- Manual code review
- Finding validation
- Post-remediation verification
<b>Findings:</b>
- Dependency CVEs
- DOM XSS
- CSP/CORS misconfiguration
- Mass assignment
- Insecure JWT session persistence
</td>
</tr>
</table>

🔴 OWASP Juice Shop — Black-Box Pentest
A hands-on black-box assessment focused on identifying and documenting exploitable application vulnerabilities.
Findings included:
BOLA / IDOR User Enumeration Brute Force Rate-Limiting Flaws SSRF
Deliverables:
- Attack-chain documentation
- Evidence for findings
- CVSS scoring
- Root-cause analysis
- Remediation guidance
- Structured Markdown/PDF report
🏗️ SecureDocs Security Architecture
                         ┌──────────────────┐
                         │      Client      │
                         └────────┬─────────┘
                                  │
                                  ▼
                         ┌──────────────────┐
                         │   Express API    │
                         │  Helmet / CORS   │
                         └────────┬─────────┘
                                  │
                    ┌─────────────┴─────────────┐
                    ▼                           ▼
             ┌──────────────┐           ┌──────────────┐
             │ JWT Auth     │           │ Rate Limiter │
             │ Middleware   │           │ + Lockout    │
             └──────┬───────┘           └──────────────┘
                    │
                    ▼
             ┌──────────────┐
             │ Authorization│
             │ RBAC + Owner │
             │ Validation   │
             └──────┬───────┘
                    │
              ┌─────┴─────────┐
              ▼               ▼
       ┌──────────────┐ ┌──────────────┐
       │ PostgreSQL   │ │    Redis     │
       │ Users        │ │ Sessions     │
       │ Documents    │ │ Revocation   │
       │ Audit Logs   │ │ OTP / Cache  │
       └──────────────┘ └──────────────┘
Security controls implemented
Layer	Controls
Authentication	JWT verification, refresh-token rotation, replay detection
Authorization	RBAC + document ownership validation
Session Security	Redis-backed revocation/session store
Abuse Prevention	Rate limiting + temporary account lockout
Password Recovery	Hashed OTPs, 5-minute TTL, rate-limited verification
File Security	MIME validation, extension allowlist, randomized filenames, quota enforcement
Browser/API Security	Helmet, CORS restrictions, secure HttpOnly cookies
Auditing	User, timestamp and IP-based audit events
Threat Modeling	STRIDE-driven security decisions


⚙️ Secure CI/CD Pipeline
Developer Push
      │
      ▼
 GitHub / Jenkins
      │
      ├── ESLint
      ├── Jest
      ├── npm audit ────────► Dependency Security
      ├── Semgrep ──────────► SAST
      ├── Gitleaks ─────────► Secret Detection
      ├── Trivy ────────────► Container Scanning
      └── Syft ─────────────► SBOM Generation
      │
      ▼
 Security Validation
      │
      ▼
 Deployment / DAST
Security tooling:
Semgrep Snyk npm audit Gitleaks Trivy Syft OWASP ZAP
Deployment and DAST stages are currently being developed.

🎯 Vulnerability Coverage
Authentication
├── JWT attacks
├── Session security
├── Authentication bypass
└── User enumeration

Authorization
├── BOLA / IDOR
├── Broken Access Control
├── Mass Assignment
└── Privilege Escalation

Injection
├── SQL Injection
├── XSS
└── SSTI

Server-Side
├── SSRF
└── Path Traversal

File Security
└── File Upload Bypass
🧪 Security Testing
Category	Tools / Technologies
Web & API Pentesting	Burp Suite, OWASP ZAP
SAST	Semgrep
SCA	Snyk, npm audit
Secret Detection	Gitleaks
Container Security	Trivy
SBOM	Syft
Network Security	Nmap, Wireshark, Netcat
Exploitation	Metasploit
Enumeration	Nuclei, ffuf, Gobuster, Nikto
Password / Hash Testing	Hashcat, John the Ripper


🛡️ Security Areas
Area	Focus
🌐 Web Security	OWASP Top 10, XSS, SQLi, SSRF, SSTI, IDOR/BOLA
🔌 API Security	Authentication, authorization, JWT, access control
🔐 Identity	Sessions, cookies, JWT, RBAC
🧪 Security Testing	SAST, SCA, DAST, manual validation
🐳 Container Security	Docker, image scanning, container hardening
⚙️ CI/CD Security	SAST, dependency scanning, secrets, SBOM
🏗️ AppSec	Secure SDLC, STRIDE, architecture reviews
🔎 Pentesting	Burp Suite, Nmap, Nuclei, ffuf, Metasploit


🧰 Technical Stack
Application Security
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="45" height="45" alt="Linux"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="45" height="45" alt="Python"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="45" height="45" alt="JavaScript"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="45" height="45" alt="Node.js"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" width="45" height="45" alt="Docker"/>
</p>

OWASP Burp Suite OWASP ZAP Semgrep Snyk Gitleaks Trivy Syft
Backend & Infrastructure
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="45" height="45" alt="Node.js"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" width="45" height="45" alt="Express"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" width="45" height="45" alt="PostgreSQL"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" width="45" height="45" alt="MongoDB"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" width="45" height="45" alt="Redis"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" width="45" height="45" alt="Nginx"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="45" height="45" alt="Git"/>
</p>

Node.js Express.js PostgreSQL MongoDB Redis Docker Docker Compose Nginx Git GitHub Actions Jenkins REST APIs
📊 GitHub Analytics
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SharmaPrem9567&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" height="180"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SharmaPrem9567&layout=compact&hide_border=true&langs_count=8" height="180"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.demolab.com?user=SharmaPrem9567&hide_border=true" height="180"/>
</p>

📈 Contribution Activity
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SharmaPrem9567&hide_border=true&area=true" width="100%"/>
</p>

🐍 Contribution Snake
<p align="center">
  <img src="https://raw.githubusercontent.com/SharmaPrem9567/SharmaPrem9567/output/github-contribution-grid-snake.svg" alt="GitHub contribution snake"/>
</p>

The snake image is generated by the GitHub Actions workflow included with this profile repository.

📌 GitHub Overview
<p align="center">
  <a href="https://github.com/SharmaPrem9567?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-View%20All-181717?style=for-the-badge&logo=github"/>
  </a>
  <a href="https://github.com/SharmaPrem9567?tab=stars">
    <img src="https://img.shields.io/badge/Starred%20Projects-View-181717?style=for-the-badge&logo=github"/>
  </a>
  <a href="https://github.com/SharmaPrem9567?tab=projects">
    <img src="https://img.shields.io/badge/Projects-View-181717?style=for-the-badge&logo=github"/>
  </a>
</p>

🧪 Security Labs & Practice
PortSwigger Web Security Academy
30+ hands-on labs covering:
SQL Injection XSS SSRF JWT Attacks Authentication Bypass Broken Access Control
TryHackMe
<a href="https://tryhackme.com/p/Blastoiz">
  <img src="https://img.shields.io/badge/TryHackMe-Blastoiz-red?style=for-the-badge&logo=tryhackme"/>
</a>

Hands-on practice across:
- Web Application Security
- Network Security
- Linux
- Enumeration
- Exploitation
- Privilege Escalation
- Active Directory
- Defensive Security
Selected Attack Chains
VulnNet: DotPy
SSTI → RCE → Privilege Escalation → Root

RootMe
File Upload → RCE → SUID Privilege Escalation → Root

Overpass
Session Authentication Flaw → Unauthorized Admin Access
Hack The Box
Hands-on practice with vulnerable machines, enumeration, exploitation and privilege escalation.
✍️ Security Writeups
I document what I learn instead of simply completing labs.
Topics include:
- 🔥 XSS exploitation & filter bypass
- 💉 SQL Injection — manual & automated
- 🔐 JWT attacks & session security
- 🆔 IDOR / BOLA
- 🛡️ Authentication & authorization
- 🌐 API security
- 🐳 Docker security
- ⚙️ CI/CD security
- 🖥️ Linux privilege escalation
- 🎯 Full CTF attack chains
- 📊 CVSS-based vulnerability reporting
- 🔧 Root-cause analysis & remediation
Medium
<a href="https://medium.com/@premwork25">
  <img src="https://img.shields.io/badge/Read%20My%20Articles-Medium-black?style=for-the-badge&logo=medium"/>
</a>

🧠 Security Engineering Mindset
Recon
  ↓
Enumeration
  ↓
Attack Surface Mapping
  ↓
Vulnerability Discovery
  ↓
Exploitation
  ↓
Impact Analysis
  ↓
Remediation
  ↓
Verification
  ↓
Detection
  ↓
Security Architecture
I don't want to stop at:
"I found a vulnerability."

The goal is to understand:
Why did it happen? → How can it be exploited? → What's the impact? → How should it be fixed? → How can the fix be verified? → How can we detect it? → How do we prevent it architecturally?
📚 Currently Learning
- Application Security Engineering
- Threat Modeling
- Secure API Design
- Security Architecture
- CI/CD Security
- Container Security
- Cloud Security
- Detection Engineering
- Advanced Web Exploitation
💻 Developer Background
My backend development experience is the foundation of my move into application security.
Development
JavaScript Node.js Express.js REST APIs
Databases
PostgreSQL MongoDB MySQL Redis
Infrastructure & DevOps
Linux Docker Docker Compose Nginx Git GitHub Actions Jenkins
Backend Engineering
Modular Architecture Authentication Authorization Caching Rate Limiting Pagination API Design
This background lets me approach security from both sides:
Build the application → Understand the architecture → Attack the application → Fix the vulnerability → Verify the fix.
🤝 Connect With Me
<p align="center">
  <a href="https://linkedin.com/in/prem-appsec">
    <img src="https://img.shields.io/badge/LinkedIn-Prem%20Sharma-0A66C2?style=for-the-badge&logo=linkedin"/>
  </a>
  <a href="https://medium.com/@premwork25">
    <img src="https://img.shields.io/badge/Medium-@premwork25-black?style=for-the-badge&logo=medium"/>
  </a>
  <a href="https://github.com/SharmaPrem9567">
    <img src="https://img.shields.io/badge/GitHub-SharmaPrem9567-181717?style=for-the-badge&logo=github"/>
  </a>
</p>

<h3 align="center">
🔐 Build. Break. Secure.
</h3>

<p align="center">
  <sub>Building backend systems, breaking them from an attacker's perspective, and engineering the controls that make them harder to break.</sub>
</p>
