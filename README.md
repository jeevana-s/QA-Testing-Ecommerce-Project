 🧪 E-commerce Sales Analytics Testing & Validation

📌 Project Overview
This project focuses on performing **manual testing** on an E-commerce Sales Analytics system. The goal is to validate SQL queries, data processing workflows, and dashboard outputs to ensure accuracy and reliability of business insights.

---

 🎯 Objectives
- Validate SQL query results and data accuracy  
- Identify defects in data processing and reporting  
- Ensure proper functioning of dashboards and analytics  
- Perform end-to-end testing of data workflows  

---

 🛠️ Tools & Technologies
- SQL  
- Microsoft Excel  
- Power BI (Dashboard validation)  

---
 📋 Test Cases
The following test cases were designed and executed:

| TC_ID | Module | Scenario | Input | Expected | Actual | Status |
|------|--------|----------|-------|----------|--------|--------|
| TC01 | SQL | Monthly sales query | Run query | Correct totals | Correct | Pass |
| TC02 | SQL | Sales by region | Execute query | Valid data | Correct | Pass |
| TC03 | SQL | Repeat customers | Query execution | Accurate count | Wrong | Fail |
| TC04 | Data | Clean dataset | Load CSV | No nulls | Some nulls | Fail |
| TC05 | Dashboard | Sales chart | Load PBIX | Correct graph | Correct | Pass |
| TC06 | Dashboard | Category filter | Apply filter | Correct results | Correct | Pass |
| TC07 | SQL | Aggregation | GROUP BY | Accurate sum | Correct | Pass |
| TC08 | Performance | Large dataset | Run queries | Fast execution | Slow | Fail |

---

 🐞 Bug Report

 Bug 1
- Module: SQL  
- Issue: Repeat customer query returns incorrect results  
- Severity: High  

 Bug 2
- Module: Data Cleaning  
- Issue: Null values present in dataset  
- Severity: Medium  

 Bug 3
- Module: Performance  
- Issue: Slow execution for large dataset queries  
- Severity: Medium  

---

 🔄 Testing Approach
- Designed and executed manual test cases  
- Validated SQL queries and data outputs  
- Identified defects and categorized them based on severity  
- Tested complete data pipeline from data loading to dashboard visualization  

---

 ✅ Outcome
- Improved data accuracy and validation  
- Identified critical issues in SQL queries and data processing  
- Ensured reliability of analytics dashboard outputs  

---

 📁 Files Included
- `QA_Testing_Project.xlsx` – Test cases and bug report  

---

 🚀 Conclusion
This project demonstrates practical knowledge of **Manual Testing, SQL validation, and data analytics testing**, aligning with real-world QA processes.
