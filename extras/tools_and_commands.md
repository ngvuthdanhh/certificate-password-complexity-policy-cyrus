# Tools and Commands for Analysis

**Email Header Analysis:**
- `mxtoolbox.com` – Online header analyzer
- `exim -Mvh <message-id>` – View headers (Linux mail server)
- Thunderbird / Outlook – Built-in header viewing

**Command-line Tools:**
- `dig TXT domain.com` – Check SPF/DKIM/DMARC records
- `whois domain.com` – Identify domain ownership
- `curl -I http://phishing-link.com` – Inspect redirects

**Lab Tools:**
- Wireshark – Capture and analyze SMTP traffic
- Python `email` library – Parse headers programmatically
