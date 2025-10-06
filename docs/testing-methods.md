# Testing Methods for Password Policy

## 🔍 Goals
- Verify that weak passwords are rejected.  
- Validate lockout and throttling mechanisms.  
- Assess resistance against brute force and dictionary attacks.

## 🛠️ Testing Approaches
1. **Brute Force**  
   - Tools: `hydra`, `hashcat`, `John the Ripper`.  
   - Measure how long it takes to crack.  

2. **Dictionary Attack**  
   - Test against common password lists (e.g., `rockyou.txt`).  
   - Ensure blacklisted/common passwords are blocked.  

3. **Hybrid Attack**  
   - Combine dictionary words with numbers/suffixes (e.g., `Password123`).  

4. **Rainbow Table Check**  
   - Validate whether password storage uses salted hashing.  

## 📊 Demo Scenarios
- Weak policy (8 characters, no complexity) → cracked within minutes.  
- Strong policy (12+ chars, mixed complexity) → estimated cracking time: thousands of years with GPUs.  
- MFA enabled → brute-force attempts become ineffective even with weak passwords.
