# Transport Layer Analysis

Phishing emails travel through multiple servers before reaching the recipient.  
The transport mechanism can reveal evidence of tampering or malicious origin.

**Important Headers:**
- `Received`: shows the path of the email across servers.
- `Return-Path`: indicates the sender’s envelope address.
- `Message-ID`: often mismatched in fake emails.

**Security Mechanisms:**
- SPF (Sender Policy Framework)
- DKIM (DomainKeys Identified Mail)
- DMARC (Domain-based Message Authentication, Reporting & Conformance)

Analyzing these headers allows investigators to validate authenticity.
