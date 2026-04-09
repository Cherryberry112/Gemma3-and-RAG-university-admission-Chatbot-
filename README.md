# 🎓 EWU Admission Chatbot (Gemma 3 + RAG + Fine-Tuning)

This repository contains a complete implementation of an AI-powered university admission chatbot built using:

- Gemma 3 (LLM)
- Retrieval-Augmented Generation (RAG)
- Fine-tuning with structured university data

---

## 📁 Repository Structure

├── Data file for RAG/
│   ├── dynamic_Admission.md
│   ├── dynamic_admission_calender.md
│   ├── dynamic_events.md
│   ├── dynamic_faculty.md
│   ├── dynamic_gradin.md
│   ├── static_AllAvailablePrograms.md
│   ├── static_Career_Counseling_Center.md
│   ├── static_Departments.md
│   ├── static_Policy.md
│   ├── static_Programs.md
│   ├── static_Rules.md
│   ├── static_Sexual_harassment.md
│   ├── static_Tuition_fees.md
│   ├── static_aboutEWU.md
│   ├── static_admission_process.md
│   ├── static_alumni.md
│   ├── static_campus_life.md
│   ├── static_clubs.md
│   ├── static_facilities.md
│   ├── static_helpdesk.md
│   ├── static_payment_procedure.md
│   ├── static_scholarship_and_financial.md
│
├── gemma3 fine tune data/
│   ├── dynamic_admission.jsonl
│   ├── dynamic_admission_calender.jsonl
│   ├── dynamic_events.jsonl
│   ├── dynamic_facilities.jsonl
│   ├── dynamic_grading.jsonl
│   ├── generic.jsonl
│   ├── static_AllAvailablePrograms.jsonl
│   ├── static_Career_Counseling_Center.jsonl
│   ├── static_Departments.jsonl
│   ├── static_Policy.jsonl
│   ├── static_Programs.jsonl
│   ├── static_Rules.jsonl
│   ├── static_Sexual_harassment.jsonl
│   ├── static_Tuition_fees.jsonl
│   ├── static_aboutEWU.jsonl
│   ├── static_alumni.jsonl
│   ├── static_campus_life.jsonl
│   ├── static_clubs.jsonl
│   ├── static_facilities.jsonl
│   ├── static_helpdesk.jsonl
│   ├── static_payment_procedure.jsonl
│   ├── static_scholarship_and_financial.jsonl
│
├── ewu-chatbot-gemma3-rag.ipynb
├── fine-tuning-gemma3.ipynb
├── README.md


---

##  Features

-  Conversational chatbot for EWU admission queries  
-  RAG-based retrieval system 
-  Fine-tuned Gemma 3 model for domain-specific responses  

---

### Fine-Tuning
- Uses `.jsonl` structured data
- Trains Gemma 3 to:
  - Understand EWU-specific terminology
  - Provide more precise and contextual responses

---

##  Data Organization

### 🔹 Static Data
Includes fixed information:
- Programs  
- Tuition fees  
- Policies  
- Campus facilities  
- Scholarships  

### 🔹 Dynamic Data
Includes frequently changing info:
- Admission deadlines  
- Academic calendar  
- Events  
- Grading system  

---

##  Notebooks

###  `fine-tuning-gemma3.ipynb`
- Prepares dataset  
- Formats JSONL training data  
- Fine-tunes Gemma 3 model  

###  `ewu-chatbot-gemma3-rag.ipynb`
- Implements full chatbot pipeline  
- Connects:
  - RAG retrieval  
  - Fine-tuned model  
- Runs interactive Q&A system  

---

##  Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2. Install Dependencies
pip install -r requirements.txt

(Create a requirements.txt if not already available)

