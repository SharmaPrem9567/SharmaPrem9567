<div align="center">

👋 Hi, I'm Prem Sharma
Backend Developer · API Security · Application Security
I build backend systems, break them from an attacker's perspective, and engineer the controls that make them harder to break.

<a href="https://github.com/SharmaPrem9567">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>
<a href="https://linkedin.com/in/prem-appsec">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="https://medium.com/@premwork25">
  <img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium">
</a>




<img src="https://komarev.com/ghpvc/?username=SharmaPrem9567&style=for-the-badge&color=0A66C2&label=PROFILE+VIEWS" alt="Profile views">

</div>

🧭 What I Do
<table>
<tr>
<td width="25%" align="center">

🔐 Web & API Security
OWASP Top 10
API Security
BOLA / IDOR
Authentication
</td>
<td width="25%" align="center">

🛡️ Secure Backend
Node.js · Express
PostgreSQL · Redis
REST APIs
Secure Auth
</td>
<td width="25%" align="center">

🎯 Vulnerability Assessment
SAST · SCA · DAST
Manual Testing
Remediation
Verification
</td>
<td width="25%" align="center">

⚙️ Security Engineering
Docker
CI/CD Security
Threat Modeling
Secure Architecture
</td>
</tr>
</table>

🚀 Featured Projects
<table>
<tr>
<td width="50%" valign="top">

🔐 SecureDocs
Secure Document Management API
A backend application where security controls are designed into the architecture instead of added later.
Engineering
- 20+ REST API endpoints
- Modular controller/service architecture
- PostgreSQL schema design
- Redis cache-aside pattern
- Pagination
- Dockerized backend
Security
- JWT authentication
- Refresh-token rotation
- Redis session/revocation store
- Replay-attack detection
- RBAC + ownership authorization
- Rate limiting + temporary lockout
- Secure password-reset OTP flow
- Audit logging
- Secure file-upload controls
<a href="https://github.com/SharmaPrem9567/SecureDocs">
<img src="https://img.shields.io/badge/View_Repository-0A66FF?style=for-the-badge&logo=github&logoColor=white">
</a>

</td>

<td width="50%" valign="top">

🔍 SecureVault
Node.js REST API Security Assessment
A security assessment of a locally-run Node.js REST API using automated and manual application-security testing.
Assessment
- SAST with Semgrep
- SCA with Snyk + npm audit
- DAST with OWASP ZAP
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

<tr>
<td colspan="2">

🔴 OWASP Juice Shop — Black-Box Pentest
Hands-on black-box assessment focused on identifying, validating and documenting exploitable web vulnerabilities.
Coverage: BOLA / IDOR · User Enumeration · Brute Force · Rate Limiting · SSRF
Deliverables: attack-chain documentation · evidence · CVSS scoring · root-cause analysis · remediation guidance · structured report
</td>
</tr>
</table>

🏗️ SecureDocs — Security by Design
<table>
<tr>
<th>Layer</th>
<th>Security Controls</th>
</tr>
<tr>
<td><b>Authentication</b></td>
<td>JWT verification · refresh-token rotation · replay detection</td>
</tr>
<tr>
<td><b>Authorization</b></td>
<td>RBAC · document ownership validation</td>
</tr>
<tr>
<td><b>Session Security</b></td>
<td>Redis-backed session/revocation store</td>
</tr>
<tr>
<td><b>Abuse Prevention</b></td>
<td>Rate limiting · temporary account lockout</td>
</tr>
<tr>
<td><b>Password Recovery</b></td>
<td>Hashed OTPs · 5-minute TTL · rate-limited verification</td>
</tr>
<tr>
<td><b>File Security</b></td>
<td>MIME validation · extension allowlist · randomized filenames · quotas</td>
</tr>
<tr>
<td><b>API Security</b></td>
<td>Helmet · CORS restrictions · secure HttpOnly cookies</td>
</tr>
<tr>
<td><b>Auditing</b></td>
<td>User · timestamp · IP-based audit events</td>
</tr>
<tr>
<td><b>Threat Modeling</b></td>
<td>STRIDE-driven security decisions</td>
</tr>
</table>

⚙️ Secure CI/CD Pipeline
Developer Push
      │
      ▼
 GitHub / Jenkins
      │
      ├── ESLint ───────┐
      ├── Jest ─────────┤
      └── npm audit ────┤
                        ▼
                     Semgrep
                      SAST
                        │
             ┌──────────┴──────────┐
             ▼                     ▼
          Gitleaks               Trivy
       Secret Detection       Container Scan
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
                 DAST / OWASP ZAP
Security tooling: Semgrep · Snyk · npm audit · Gitleaks · Trivy · Syft · OWASP ZAP
Deployment and DAST stages are currently being developed.

🎯 Vulnerabilities I've Practiced
<table>
<tr>
<td width="25%" valign="top">

🔐 Authentication
- JWT attacks
- Session security
- Authentication bypass
- User enumeration
</td>
<td width="25%" valign="top">

🛡️ Authorization
- BOLA / IDOR
- Broken access control
- Mass assignment
- Privilege escalation
</td>
<td width="25%" valign="top">

💉 Injection
- SQL Injection
- XSS
- SSTI
</td>
<td width="25%" valign="top">

🌐 Server-Side
- SSRF
- Path traversal
- File-upload bypass
</td>
</tr>
</table>

🧪 Security Testing Toolkit
<table>
<tr>
<td valign="top" width="50%">

🌐 Web & API Pentesting
Burp Suite · OWASP ZAP · Nmap · Nuclei
ffuf · Gobuster · Nikto · SQLmap
Metasploit · Wireshark · Netcat
</td>
<td valign="top" width="50%">

🛡️ Application Security
Semgrep · Snyk · npm audit · Gitleaks
Trivy · Syft · OWASP Top 10 · STRIDE
</td>
</tr>
<tr>
<td valign="top">

🎓 Platforms
TryHackMe · Hack The Box
PortSwigger Web Security Academy
OverTheWire
</td>
<td valign="top">

🧰 Backend & Infrastructure
Node.js · Express.js · PostgreSQL
MongoDB · MySQL · Redis
Docker · Docker Compose · Nginx
Git · GitHub Actions · Jenkins
</td>
</tr>
</table>

🧠 Security Labs & Attack Chains
PortSwigger Web Security Academy
30+ hands-on labs covering:
SQL Injection · XSS · SSRF · JWT Attacks · Authentication Bypass · Broken Access Control
TryHackMe
<a href="https://tryhackme.com/p/Blastoiz">
<img src="https://img.shields.io/badge/TryHackMe-Blastoiz-D92B2B?style=for-the-badge&logo=tryhackme&logoColor=white">
</a>

Selected attack chains
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
Topic	Focus
🔥 XSS	Exploitation & filter bypass
💉 SQL Injection	Manual & automated testing
🔐 JWT	Token attacks & session security
🆔 IDOR / BOLA	Broken object-level authorization
🛡️ Authentication	Authentication & authorization
🌐 API Security	API attack surface & controls
🐳 Docker Security	Container security
⚙️ CI/CD Security	Pipeline security
🖥️ Linux	Privilege escalation
🎯 CTFs	Full attack chains
📊 Vulnerability Reporting	CVSS-based reporting
🔧 Remediation	Root-cause analysis & verification


<a href="https://medium.com/@premwork25">
<img src="https://img.shields.io/badge/Read_My_Articles-000000?style=for-the-badge&logo=medium&logoColor=white">
</a>

📊 GitHub Analytics
<div align="center">

<a href="https://github.com/SharmaPrem9567">
<img height="180" src="https://github-readme-stats.vercel.app/api?username=SharmaPrem9567&show_icons=true&include_all_commits=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub statistics">
</a>

<a href="https://github.com/SharmaPrem9567">
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SharmaPrem9567&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Most used languages">
</a>




<img src="https://streak-stats.demolab.com?user=SharmaPrem9567&theme=tokyonight&hide_border=true" alt="GitHub contribution streak">

</div>

GitHub's native contribution graph remains available directly on my profile.

💻 Backend Engineering
My backend development experience is the foundation of my move into Application Security.
<table>
<tr>
<td width="25%" valign="top">

Development
JavaScript
Node.js
Express.js
REST APIs
</td>
<td width="25%" valign="top">

Databases
PostgreSQL
MongoDB
MySQL
Redis
</td>
<td width="25%" valign="top">

Infrastructure
Linux
Docker
Docker Compose
Nginx
</td>
<td width="25%" valign="top">

Engineering
Authentication
Authorization
Caching
Rate Limiting
Pagination
API Design
</td>
</tr>
</table>

📚 Currently Learning
Application Security
├── Secure API Design
├── Threat Modeling
├── Security Architecture
├── CI/CD Security
├── Container Security
├── Cloud Security
├── Detection Engineering
└── Advanced Web Exploitation
🧭 My Security Workflow
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
I don't want to stop at: "I found a vulnerability."

I want to understand:
Why did it happen? → How can it be exploited? → What's the impact? → How should it be fixed? → How can the fix be verified? → How can we detect it? → How do we prevent it architecturally?
🤝 Let's Connect
<div align="center">

<a href="https://linkedin.com/in/prem-appsec">
<img src="https://img.shields.io/badge/LinkedIn-Prem_Sharma-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
<a href="https://medium.com/@premwork25">
<img src="https://img.shields.io/badge/Medium-@premwork25-000000?style=for-the-badge&logo=medium&logoColor=white">
</a>
<a href="https://github.com/SharmaPrem9567">
<img src="https://img.shields.io/badge/GitHub-SharmaPrem9567-181717?style=for-the-badge&logo=github&logoColor=white">
</a>




🔐 Build. Break. Secure.
Backend engineering + offensive security + secure architecture.
</div>
