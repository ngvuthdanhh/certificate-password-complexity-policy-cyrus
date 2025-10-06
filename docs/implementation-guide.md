# Password Policy Implementation Guide

## 🖥️ Operating Systems

- **Windows (Active Directory):**
  - Navigate to: Group Policy → Computer Configuration → Windows Settings → Security Settings → Account Policies → Password Policy.  
  - Example: MinLength = 12, Complexity = Enabled, MaxAge = 90 days.  

- **Linux (PAM):**
  - Edit `/etc/security/pwquality.conf`.  
  - Example: `minlen=12`, `dcredit=-1`, `ucredit=-1`, `lcredit=-1`, `ocredit=-1`.  

- **macOS:**
  - Use `pwpolicy` tool.  
  - Example: `pwpolicy -setglobalpolicy "minChars=12 requiresMixedCase=1 requiresNumeric=1 requiresSymbol=1"`  

## 🌐 Directory Services
- Add password policy object (`pwdPolicy`) in LDAP to enforce rules across users/OU.  
- Configure lockout after 5 failed attempts.  
- Always use MFA alongside password policies.

## 📝 Example Policy
- Minimum 12 characters.  
- At least 1 uppercase, 1 lowercase, 1 digit, 1 special character.  
- Not part of top 10,000 most common passwords.  
- Must not contain username or personal data (e.g., birthday).
