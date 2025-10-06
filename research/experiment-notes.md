# Experiment Notes

## Purpose
This file tracks experiments, tests, and case studies performed during the course of studying phishing emails and password complexity policies.

---

### Template for Each Experiment

**Experiment ID:**  
**Date:**  
**Objective:**  
**Setup / Environment:**  
- Tools used  
- Configurations  
- Dataset or sample  

**Procedure:**  
Step-by-step actions taken.  

**Observations:**  
- What was seen during the test.  
- Unexpected behaviors.  

**Results:**  
- Key findings  
- Screenshots or hashes (if available)  

**Conclusion / Next Steps:**  
- Lessons learned  
- Further improvements  

---

### Example Entry

**Experiment ID:** EXP-01  
**Date:** 2025-10-05  
**Objective:** Test the effect of weak vs strong password policies on brute force attempts.  

**Setup / Environment:**  
- Windows 10 VM + Local Security Policy  
- John the Ripper for brute force test  
- User accounts: `weakUser`, `strongUser`  

**Procedure:**  
1. Applied weak password policy (min length = 6, no complexity).  
2. Created account `weakUser` with password `abc123`.  
3. Applied strong password policy (length = 12, with complexity).  
4. Created account `strongUser` with password `Q9!tHr6&vLz2`.  
5. Ran brute force on both accounts.  

**Observations:**  
- Weak password cracked instantly.  
- Strong password resisted dictionary + brute force test.  

**Results:**  
- Weak policies expose users to trivial compromise.  
- Strong policies dramatically increase cracking time.  

**Conclusion / Next Steps:**  
- Reinforce the importance of MFA to complement strong passwords.  
- Extend test to Linux PAM in next experiment.  
