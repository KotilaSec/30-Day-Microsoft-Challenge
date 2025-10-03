# MyDFIR 30-Day Microsoft Challenge

This repo documents my 30-day journey through Microsoft 365 E5, Azure, Sentinel, Defender XDR, and Intune.  
Goal: Build hands-on skills and a portfolio for SOC roles (investigations, analysis, incident response).

---

## Progress Log

**Day 1**
- MS 365 E5 Trial – Done  
- Azure $200 Credit – Done  
- Billing Alerts – Done  
- Goal: Practical experience with cloud security and SOC workflows.

**Days 2–4**
- Created Azure VM, secured RDP.  
- Built Sentinel workspace.  
- Loaded training data, started KQL.  

**Day 4 (Detail)**
- Wrote query on `EmailEvents` to check SPF/DKIM/DMARC.  
- Learned how to parse `AuthenticationDetails`.  

**Day 6**
- Installed Defender XDR.  
- Waiting for data connector to appear (still troubleshooting).  

**Day 7**
- Investigation: 18k failed logins within one second.  
- Hosts: SOC-FW-RDP, SHIR-Hive, SHIR-SAP.  
- Recommendation: Restrict RDP, enforce MFA/VPN, enable account lockouts, add alerts.

---

## Next Steps
- Add more KQL queries
- Continue daily logs
- Build out small investigations
