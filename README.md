# Aviation-GPT

Privacy Policy for Aviation GPT
Last updated: July 29, 2025

1. Introduction
Aviation GPT (“we”, “our”, or “the Service”) is a custom ChatGPT assistant designed to help pilots by providing FAA regulations, weather briefings, and aircraft‑specific guidance. This Privacy Policy explains how we collect, use, disclose, and protect your information when you interact with our Service.

2. Information We Collect
2.1 User‑Provided Information
Chat Inputs: All questions, commands, and station identifiers (e.g., ICAO codes) you type into Aviation GPT.

Account Data: If you sign in or register, we may collect your username, email address, and profile details.

2.2 Automatically Collected Data
Usage Logs: Timestamps, pages or endpoints accessed (e.g., /metar?station=KSTL), and error reports.

Technical Data: IP address, browser type/version, operating system, and device identifiers for security and analytics.

3. How We Use Your Information
Provide & Improve the Service: Generate accurate regulatory, procedural, and weather responses; debug and optimize performance.

API Calls: Forward station codes to third‑party endpoints (Replit proxy, AviationWeather.gov) to retrieve METAR/TAF data.

Analytics: Monitor usage patterns to identify popular features and troubleshoot issues.

4. Third‑Party Services & Data Sharing
Replit Hosting: Your station queries are passed to our Flask proxy on Replit (metar, taf endpoints). Replit may log requests per their own policies.

AviationWeather.gov: Raw requests to fetch METAR/TAF; these third parties may collect request metadata (e.g., your IP).

Uptime Monitoring (optional): If you use a service like UptimeRobot, its periodic pings keep the proxy awake and may log your endpoint URLs.

No Other Sharing: We do not sell or rent your personal data. We only share what’s necessary to fulfill your request.

5. Data Retention & Deletion
Chat Logs: Retained for up to 90 days to support debugging and analytics, then automatically purged.

Account Data: Stored until you delete your account or request removal.

Deletion Requests: Email us at support@aviationgpt.example.com to request full deletion of your data.

6. Security Measures
Encryption: All communications with Aviation GPT and the proxy server are secured via HTTPS/TLS.

Access Controls: Limited personnel access to production logs; no hard‑coded secrets in public repos.

Regular Audits: Dependency and vulnerability scans run monthly to patch security issues.

7. User Rights & Choices
Access & Portability: You can request a copy of your chat transcripts and profile data.

Correction: Ask us to correct any factual errors or typos in your account.

Opt‑Out: You may opt out of usage analytics by contacting us; core functionality will still work.

Effective Date & Changes: We may update this policy. We’ll notify users of material changes via email or an in‑Service notice.

8. Children’s Privacy
Aviation GPT is intended for users aged 13 and above. We do not knowingly collect information from children under 13. If you believe we have inadvertently collected such data, please contact us to have it removed.
