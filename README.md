Secure Student Portal

A secure web system for managing student records, grades, and payments with strong protection against cyber threats.

📘 Overview

Developed for the Software Secured Development (CCS2323) course, this portal applies modern cybersecurity principles to ensure data confidentiality, integrity, and availability.

👩‍💻 Team
Ameer Khan Wadan (AIU22102277)
Reem Bekdash (AIU22102281)
🎯 Objectives
Secure authentication and role-based access.
Encrypted communication and storage.
Compliance with GDPR and FERPA standards.
🔐 Key Security Features
Authentication & MFA for safe logins.
RBAC to limit user access.
AES-256 & TLS 1.3 encryption.
Input validation against SQL/XSS attacks.
Session timeouts and audit logging.
🧩 Architecture

Three-layer secure design:
Frontend (UI) → Backend (API) → Encrypted Database

🧪 Testing

Security verified through:

Penetration & fuzz testing
Threat modeling (STRIDE)
Tools: OWASP ZAP, Burp Suite
⚙️ Risk Examples
Risk	Mitigation
Unauthorized access	RBAC + audit logs
DoS attacks	Load balancers
Payment fraud	Encrypted transactions
