# MyDFIR 30-Day Microsoft Challenge

This repo documents my 30-day journey through Microsoft 365 E5, Azure, Sentinel, Defender XDR, and Intune.  
Goal: Build hands-on skills and a portfolio for SOC roles (investigations, analysis, incident response).

---

## Progress Log

## [Days 1–4](https://github.com/KotilaSec/30-Day-Microsoft-Challenge/tree/main/Day%201-4)
- **Day 1** – MS 365 E5 Trial – Done  
- Azure $200 Credit – Done  
- Billing Alerts – Done  
- Goal: Gain practical experience with Microsoft cloud security and SOC workflows.  

- **Days 2–4** – Created Azure VM and secured RDP.  
- Built Microsoft Sentinel workspace.  
- Loaded training data and started KQL queries.  
- Query example: Checked `EmailEvents` for SPF/DKIM/DMARC validation.  
- Learned how to parse `AuthenticationDetails` for email authentication results.  

---

## [Days 5–8](https://github.com/KotilaSec/30-Day-Microsoft-Challenge/tree/main/Day%205-8)
- **Day 6** – Installed Defender XDR.  
  - Currently troubleshooting why the data connector has not appeared yet.  

- **Day 7** – Investigation: Detected 18k failed logins within one second.  
  - Affected hosts: `SOC-FW-RDP`, `SHIR-Hive`, `SHIR-SAP`.  
  - Recommendations:  
    - Restrict RDP to approved IPs.  
    - Enforce MFA or VPN access.  
    - Enable account lockouts.  
    - Add custom alerts in Sentinel.  

- **Day 8** – Sentinel Bookmarking.  
  - Practiced creating bookmarks to track and correlate related incidents.  
  - Used bookmarks to tag suspicious activity and save KQL query results for ongoing investigations.  
  - Organized investigation flow for easier evidence review and triage.

---

## Reflection – Days 1–8

The first eight days have been both challenging and rewarding. Setting up Azure, Sentinel, and Defender XDR gave me real hands-on experience with Microsoft’s cloud security tools not just reading about them, but actually building and troubleshooting a working environment.  

Learning KQL, connecting data sources, and performing my first investigations helped me understand how these tools fit together in a real SOC workflow. It’s one thing to watch a video, but another to see the alerts, queries, and detections come to life.  

Building and documenting everything on GitHub has been its own learning curve. This is my first time using GitHub for a public project, so figuring out repositories, Markdown formatting, image embedding, and overall structure took some effort. But now it’s starting to feel like a real portfolio something I can look back on to measure progress and share what I’ve learned.  

Overall, these first eight days built a foundation not only in cloud security tools but also in professional documentation and workflow discipline. Every step made me more confident in both my technical and presentation skills.
