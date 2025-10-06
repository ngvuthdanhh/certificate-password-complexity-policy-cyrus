# Case Study: Suspicious Email

**Scenario:**  
A user reports receiving an email from "IT Support" requesting password reset.

**Investigation Steps:**
1. Review headers – mismatch between `From:` and `Received:` domains.
2. Check SPF/DKIM results – failed authentication.
3. Inspect links – redirects to a fake login page.
4. Outcome – Confirmed phishing attempt.

**Lesson Learned:**
Always verify technical indicators and educate users on suspicious patterns.
