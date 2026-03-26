# 🧠 Case Study: Resolving VMware VM Performance & Disk Alert Issues

## 📌 Overview
Handled performance degradation and disk-related alerts in a VMware environment impacting virtual machine stability.

---

## 🚨 Problem Statement
- Users reported slow system performance  
- Alerts triggered for low disk space and high resource usage  
- Risk of application downtime and degraded user experience  

---

## 🔍 Investigation

### Initial Checks
- Reviewed alerts in vCenter  
- Checked VM CPU, RAM, and disk utilization  
- Identified high disk usage and snapshot accumulation  

### Deep Dive Analysis
- Found unused/old snapshots consuming storage  
- Observed datastore nearing capacity  
- Detected uneven resource allocation across VMs  

---

## 🛠 Actions Taken
- Cleaned up unnecessary snapshots  
- Performed disk expansion for critical VMs  
- Balanced resource allocation (CPU/RAM)  
- Monitored VM performance post-changes  

---

## ✅ Resolution
- Disk space issues resolved  
- VM performance stabilized  
- Alerts cleared from monitoring system  

---

## 📈 Impact
- Improved system performance and responsiveness  
- Prevented potential downtime due to storage exhaustion  
- Reduced recurring alerts and admin overhead  

---

## 🎯 Key Learnings
- Snapshot management is critical in VMware environments  
- Monitoring datastore usage prevents major incidents  
- Proactive checks reduce production issues  

---

## 💡 Tools Used
- VMware vCenter  
- VMware vSphere  
