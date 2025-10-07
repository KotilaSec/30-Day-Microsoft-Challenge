## 📈 **Day 5 – Sentinel Dashboards**
- Created dashboards under **Threat Management → Workbooks**  
- Two dashboards built (limited data so far)  

---

## 🛡️ **Day 6 – Microsoft Defender XDR**
- Installed **Microsoft Defender XDR**  
- Created **alert rule for failed logons**

![Day 6 Image](https://raw.githubusercontent.com/KotilaSec/30-Day-Microsoft-Challenge/main/Day%205-8/images/day6img.png)

---

## 🔍 **Day 7 – KQL Investigation**
**Reference:** [Summary Document](https://docs.google.com/document/d/1pY7sVFVbKiiCF-gDWJIdcChZ0H4WVu1WWZOTdysIcz4/edit?tab=t.0)

![Day 7 Image](https://github.com/KotilaSec/30-Day-Microsoft-Challenge/blob/main/Day%205-8/images/day7kqlimg.png)

![Day 7 Image](https://github.com/KotilaSec/30-Day-Microsoft-Challenge/blob/main/Day%205-8/images/day7failedimg.png)

**KQL Objectives**
1. Identify which accounts have the **most failed logons**  
2. Check for **successful logons** from those same accounts (and from where)  
3. Provide **recommendations** if this were a real client incident  

---

## 🚨 **Day 8 – Sentinel Bookmarking**
- Created **bookmark:** `SigninLogs - AccountDisabled`  
- Generated a **test incident**  
> Admin disabled the account after a login attempt from **North Korea (IP: 175.45.176.99)**  
