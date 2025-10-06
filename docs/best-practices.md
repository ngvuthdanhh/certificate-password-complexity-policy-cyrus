# Password Policy Best Practices

## ✅ User Guidelines
- Use **passphrases** instead of short random strings (e.g., `Coffee!Train!BlueSky!`).  
- Never reuse passwords across multiple services.  
- Use a password manager (Bitwarden, KeePassXC, 1Password).  

## 🔐 MFA and Layered Security
- Always combine strong passwords with MFA (OTP, FIDO2, U2F).  
- Passwords should not be the only line of defense.  

## 🔄 Rotation & Expiration
- NIST recommends **not enforcing periodic rotation** without evidence of compromise.  
- Change only when suspected breach occurs.  

## 🚨 Lockout Policy
- Temporary lockout after 5–10 failed attempts.  
- Consider progressive delays instead of permanent lockout to prevent DoS attacks.  

## 🏢 Enterprise Practices
- Regular security awareness training (e.g., phishing simulations).  
- Implement Single Sign-On (SSO) with MFA.  
- Audit Active Directory/LDAP for weak or expired credentials.
