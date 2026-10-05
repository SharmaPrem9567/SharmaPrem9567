<div align="center">

👋 Hi, I'm Prem Sharma
Backend Developer · API Security · Application Security
I build backend systems, break them from an attacker's perspective, and engineer the controls that make them harder to break.
<p>
  <a href="https://github.com/SharmaPrem9567">
    <img src="https://img.shields.io/badge/GitHub-SharmaPrem9567-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
  <a href="https://linkedin.com/in/prem-appsec">
    <img src="https://img.shields.io/badge/LinkedIn-Prem%20Sharma-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
  </a>
  <a href="https://medium.com/@premwork25">
    <img src="https://img.shields.io/badge/Medium-@premwork25-000000?style=for-the-badge&logo=medium" alt="Medium"/>
  </a>
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=SharmaPrem9567&style=flat-square&label=PROFILE+VIEWS" alt="Profile views"/>
</p>

</div>

🧑‍💻 About Me
I'm a backend developer moving deeper into Application Security, with hands-on work across secure API development, web application testing, vulnerability assessment, and CI/CD security.
My focus sits at the intersection of building applications and breaking them:
Build → Understand the Architecture → Attack → Remediate → Verify → Harden
What I work on
- 🔐 Web & API Security
- 🛡️ Application Security & Secure SDLC
- 🔑 Authentication, Authorization & Session Security
- 🎫 JWT Security & Refresh Token Rotation
- 🚨 BOLA / IDOR & Broken Access Control
- 💉 SQL Injection, XSS, SSRF & SSTI
- 🧪 SAST / SCA / DAST
- 🐳 Docker & Container Security
- ⚙️ CI/CD Security
- 🏗️ STRIDE Threat Modeling
- 🔎 Vulnerability Assessment & Web Pentesting
🚀 Featured Work
<table>
<tr>
<td width="50%" valign="top">

🔐 SecureDocs
Secure Document Management API
<a href="https://github.com/SharmaPrem9567/SecureDocs">
  <img src="https://img.shields.io/badge/VIEW%20PROJECT-181717?style=for-the-badge&logo=github" alt="SecureDocs repository"/>
</a>

Stack
Node.js Express PostgreSQL Redis Docker JWT
Backend
- 20+ REST API endpoints
- Modular controller/service architecture
- PostgreSQL schema design
- Redis cache-aside pattern
- Pagination
- Authentication & authorization
Security
- JWT verification & refresh-token rotation
- Redis session/revocation store
- Replay-attack detection
- RBAC + ownership-based authorization
- Rate limiting & temporary lockout
- Secure password-reset OTP flow
- Audit logging
- Secure file-upload controls
</td>

<td width="50%" valign="top">

🔍 SecureVault
Node.js REST API Security Assessment
Testing
Semgrep Snyk npm audit OWASP ZAP
- SAST
- SCA
- DAST
- Manual code review
- Finding validation
- Post-remediation verification
Findings
- Dependency CVEs
- DOM XSS
- CSP/CORS misconfiguration
- Mass assignment
- Insecure JWT session persistence
</td>
</tr>
</table>

🔴 OWASP Juice Shop — Black-Box Pentest
Hands-on black-box assessment focused on identifying, validating and documenting exploitable web vulnerabilities.
BOLA / IDOR · User Enumeration · Brute Force · Rate Limiting · SSRF
Deliverables: attack chains · evidence · CVSS scoring · root-cause analysis · remediation guidance · structured report
🏗️ SecureDocs: Security by Design
Instead of treating security as an afterthought, SecureDocs applies controls throughout the application lifecycle.
Layer	Controls
Authentication	JWT verification, refresh-token rotation, replay detection
Authorization	RBAC + document ownership validation
Session Security	Redis-backed session/revocation store
Abuse Prevention	Rate limiting + temporary account lockout
Password Recovery	Hashed OTPs, 5-minute TTL, rate-limited verification
File Security	MIME validation, extension allowlist, randomized filenames, quotas
API Security	Helmet, CORS restrictions, secure HttpOnly cookies
Auditing	User, timestamp and IP-based audit events
Threat Modeling	STRIDE-driven security decisions


⚙️ Secure CI/CD
                    Developer Push
                         │
                         ▼
                   GitHub / Jenkins
                         │
       ┌─────────────────┼──────────────────┐
       ▼                 ▼                  ▼
     ESLint             Jest             npm audit
       │                 │                  │
       └─────────────────┼──────────────────┘
                         ▼
                     Semgrep
                      SAST
                         │
              ┌──────────┴──────────┐
              ▼                     ▼
          Gitleaks                 Trivy
      Secret Detection        Container Scan
              │                     │
              └──────────┬──────────┘
                         ▼
                       Syft
                    SBOM Generation
                         │
                         ▼
                 Security Validation
                         │
                         ▼
                    Deployment
                         │
                         ▼
                     DAST / ZAP
Security tooling: Semgrep · Snyk · npm audit · Gitleaks · Trivy · Syft · OWASP ZAP
Deployment and DAST stages are currently being developed.

🎯 Vulnerabilities I've Practiced
<div align="center">

Authentication	Authorization	Injection	Server-Side
JWT attacks	BOLA / IDOR	SQL Injection	SSRF
Session security	Broken Access Control	XSS	Path Traversal
Authentication bypass	Mass Assignment	SSTI	
User enumeration	Privilege Escalation		


</div>

🧪 Security Testing Stack
<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,python,js,nodejs,docker,git,githubactions,jenkins,postgres,mongodb,redis,nginx&perline=6" alt="Technology stack"/>
</p>

Web & API Pentesting
Burp Suite OWASP ZAP Nmap Nuclei ffuf Gobuster Nikto SQLmap Metasploit Wireshark Netcat
Application Security
Semgrep Snyk npm audit Gitleaks Trivy Syft OWASP Top 10 STRIDE
Platforms
TryHackMe Hack The Box PortSwigger Web Security Academy OverTheWire
🧠 Security Labs & Attack Chains
PortSwigger Web Security Academy
30+ hands-on labs covering:
SQL Injection · XSS · SSRF · JWT Attacks · Authentication Bypass · Broken Access Control
TryHackMe
<a href="https://tryhackme.com/p/Blastoiz">
  <img src="https://img.shields.io/badge/TryHackMe-Blastoiz-D92B2B?style=for-the-badge&logo=tryhackme" alt="TryHackMe"/>
</a>

Selected attack chains:
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
<p align="center">
  <a href="https://medium.com/@premwork25">
    <img src="https://img.shields.io/badge/READ%20MY%20ARTICLES-000000?style=for-the-badge&logo=medium" alt="Medium"/>
  </a>
</p>

📊 GitHub Analytics
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SharmaPrem9567&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&rank_icon=github" height="180" alt="GitHub statistics"/>
  <img src="https://streak-stats.demolab.com?user=SharmaPrem9567&theme=tokyonight&hide_border=true" height="180" alt="GitHub contribution streak"/>
</p>

📈 Contribution Activity
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=SharmaPrem9567&theme=github_dark" width="100%" alt="GitHub contribution activity"/>
</p>

The card above provides a contribution/activity overview without relying on a broken static image stored in the repository.

📌 GitHub
<p align="center">
  <a href="https://github.com/SharmaPrem9567?tab=repositories">
    <img src="https://img.shields.io/badge/📦%20ALL%20REPOSITORIES-181717?style=for-the-badge" alt="All repositories"/>
  </a>
  <a href="https://github.com/SharmaPrem9567?tab=stars">
    <img src="https://img.shields.io/badge/⭐%20STARRED%20PROJECTS-181717?style=for-the-badge" alt="Starred projects"/>
  </a>
</p>

💻 Backend Engineering
My backend development experience is the foundation of my move into application security.
Development
JavaScript · Node.js · Express.js · REST APIs
Databases
PostgreSQL · MongoDB · MySQL · Redis
Infrastructure & DevOps
Linux · Docker · Docker Compose · Nginx · Git · GitHub Actions · Jenkins
Backend Engineering
Modular Architecture · Authentication · Authorization · Caching · Rate Limiting · Pagination · API Design
📚 Currently Learning
Application Security
       │
       ├── Secure API Design
       ├── Threat Modeling
       ├── Security Architecture
       ├── CI/CD Security
       ├── Container Security
       ├── Cloud Security
       ├── Detection Engineering
       └── Advanced Web Exploitation
🧭 My Security Workflow
<p align="center">

Recon → Enumeration → Attack Surface Mapping → Vulnerability Discovery
↓
Exploitation → Impact Analysis → Remediation → Verification
↓
Detection → Security Architecture
</p>

I don't want to stop at:
"I found a vulnerability."

I want to understand:
Why did it happen? → How can it be exploited? → What's the impact? → How should it be fixed? → How can the fix be verified? → How can we detect it? → How do we prevent it architecturally?
🤝 Let's Connect
<p align="center">
  <a href="https://linkedin.com/in/prem-appsec">
    <img src="https://img.shields.io/badge/LinkedIn-Prem%20Sharma-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
  </a>
  <a href="https://medium.com/@premwork25">
    <img src="https://img.shields.io/badge/Medium-@premwork25-000000?style=for-the-badge&logo=medium" alt="Medium"/>
  </a>
  <a href="https://github.com/SharmaPrem9567">
    <img src="https://img.shields.io/badge/GitHub-SharmaPrem9567-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
</p>

<div align="center">

🔐 Build. Break. Secure.
<sub>Backend engineering + offensive security + secure architecture.</sub>
</div>
