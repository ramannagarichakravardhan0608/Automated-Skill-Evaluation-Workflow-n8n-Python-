# Average Marks Calculator using n8n & Python

This project is an automated workflow built in **n8n** that collects student details, takes subject marks, calculates the **total score**, **average score**, and **skill level**, and finally checks if the student is **eligible or not**.

---

## ✅ Features

✔ Collects student details through forms  
✔ Separate workflows for *Data Analyst* and *Data Scientist*  
✔ Python code calculates:
- Total marks  
- Average marks  
- Skill level (Beginner / Intermediate / Expert)

✔ Shows final result message:
- ✅ You are eligible  
- ❌ You are not eligible  

---

## ✅ Workflow Structure

1. **Form Trigger**
   - Takes name, batch, location, and course

2. **IF Condition**
   - Checks course name
   - If "data analyst" → small form
   - Else → full form for data science subjects

3. **Python Code**
   - Converts marks to integers
   - Calculates total, average, and skill category

4. **Eligibility Check**
   - If average ≥ 50 → Eligible
   - Else → Not Eligible

---

## ✅ Tech Used
| Tool | Purpose |
|------|----------|
| n8n  | Workflow automation |
| Python | Score calculation & logic |

---

## ✅ Input Fields

### For Data Analyst:
- Python  
- EDA  
- SQL  
- Power BI  

### For Data Scientist:
- Python  
- EDA  
- SQL  
- Power BI  
- Machine Learning  
- Deep Learning  
- Gen AI  

---

## ✅ Output Example

```json
{
  "total_score": 65,
  "average_score": 8.12,
  "level": "Expert",
  "message": "You are eligible ✅"
}


✅ How to Run

Import the JSON workflow file into n8n

Open the workflow

Execute or publish the form

Enter student details and marks

View final eligibility output

✅ Author

Ramannagari Chakravardhan
Passionate about Automation, Data Science, and AI

✅ This project is a good showcase for automation + Python + workflow logic.
✅ Perfect for resume & GitHub portfolio!
