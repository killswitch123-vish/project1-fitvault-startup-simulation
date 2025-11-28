# Project 1 — FitVault Startup Simulation

## 🎯 Objective  
Build a complete fictional company (FitVault) to serve as the foundation for all IAM, RBAC, JIT, UAR, and Identity Governance projects.  
This project defines the people, structure, roles, and applications used across the organisation.

---

## 🧱 What I Built  
- Full employee directory (21 users)  
- Departments: IT, Operations, Sales, Marketing, Security, Executives  
- Job titles + role descriptions  
- Manager hierarchy & location information  
- Tool inventory for each department  
- Mapping: Department → Role → Required Applications  
- Business context for all future IAM governance work  

This becomes the baseline for all identity and access decisions.

## 📊 Key Files

### **📂 csv/**
| File | Purpose |
|------|---------|
| employee-directory.csv | List of all employees, titles, departments, and managers |
| departments-and-roles.csv | Breakdown of all departments and the roles inside each one |
| company-tools.csv | Full tool list with department usage + access justification |

### **📂 docs/**
| File | Purpose |
|------|---------|
| org-chart.png | Visual representation of company hierarchy |
| department-breakdown.md | Explanation of each department's responsibilities |

---

## 🧩 Why This Matters  
Identity Governance requires context:
- Who works at the company  
- What they do  
- What tools they need  
- What permissions match their role  

This project builds the foundation for:
- Project 2 (Tool Inventory & RBAC)  
- Project 3 (Security Groups)  
- Project 4 (JIT Access)  
- Project 5 (UAR)  
- Project 7 (Deprovisioning)
- project 8 (Azure Project)

Nothing in IAM makes sense without a well-defined business structure.

---

## 🚀 Next Project  
**Project 2 — Tool Inventory & RBAC**
