# AI Resume Analyzer (Flask Web Application)

## 📌 Project Overview
The **AI Resume Analyzer** is a web-based application developed using Python and Flask that analyzes a user’s resume and compares it with a given job description. The system evaluates skill matching, identifies missing skills, extracts structured resume sections, and provides categorized improvement suggestions similar to professional ATS (Applicant Tracking Systems).

The project is fully deployed on cloud with a permanent public URL.

---

## 🎯 Objectives
- Analyze resumes automatically using NLP-based keyword matching
- Compare resume skills with job description requirements
- Generate an ATS-style match score
- Extract structured sections from resumes
- Provide categorized improvement suggestions
- Deploy the project with a permanent public link

---

## ⚙️ Features Implemented
- Resume upload support (PDF, DOCX, TXT)
- Optional job description input with quick skill suggestion buttons
- Automatic skill extraction from resume
- Required skill detection from job description
- Resume match percentage calculation
- Categorized improvement suggestions:
  - Technical Skill Gaps
  - Soft Skills & Professional Traits
  - Resume Content & Structure
  - ATS Optimization
- Automatic resume section extraction:
  - Education
  - Experience
  - Projects
  - Skills
  - Certifications
- Clean, professional frontend UI
- Cloud deployment with permanent public access

---

## 🛠️ Technologies & Tools Used
- **Programming Language:** Python  
- **Web Framework:** Flask  
- **Frontend:** HTML, CSS, JavaScript  
- **Libraries:** PyPDF2, python-docx, Gunicorn  
- **Version Control:** Git & GitHub  
- **Deployment Platform:** Render  

---
## 📂 Project Structure
ai-resume-analyzer/
│
├── app.py
├── resume_analyzer.py
├── requirements.txt
│
├── templates/
│ ├── index.html
│ └── result.html
│
├── static/
│ └── style.css
│
├── uploads/


---

## 🚀 How the Project Works
1. User uploads a resume file
2. (Optional) User adds a job description manually or using suggestion buttons
3. The system extracts text from the resume
4. Skills are detected using keyword-based NLP logic
5. Resume skills are matched with job requirements
6. A match percentage is calculated
7. Resume sections are extracted automatically
8. Categorized improvement suggestions are generated
9. Results are displayed in a clean UI

---

## 🌐 Live Project Link
https://ai-resume-analyzer-ae3h.onrender.com

yaml
Copy code

---

## 📘 Learning Outcomes
- Hands-on experience with Flask web development
- Resume parsing and text processing
- Basic NLP techniques using keyword matching
- Cloud deployment using GitHub and Render
- Understanding of ATS-style resume evaluation
- Full-stack project development lifecycle

---

## 🔮 Future Enhancements
- Resume PDF download with improvements
- Skill weight-based scoring
- Database integration for user history
- Login and authentication
- Advanced NLP using spaCy or Transformers
- Support for multiple job profiles

---

## 👤 Author
**Shubham Dawal**  


---

## 📝 Conclusion
This project demonstrates a complete end-to-end Python web application, combining backend logic, frontend design, and cloud deployment. It simulates real-world ATS systems and provides practical resume improvement insights.

