# 🚀 AI Resume Analyzer using NLP 📄

Welcome to **AI Resume Analyzer**, a powerful tool that uses **Natural Language Processing (NLP)** to extract valuable insights from resumes. It identifies **key skills, experience, and personal details**, then categorizes them into relevant sectors. Using **keyword matching and predictive analysis**, the tool offers **personalized recommendations, career insights, and analytical reports** for both applicants and recruiters.

---

## 🌐 Tech Stack

| Component     | Technologies Used                        |
|----------------|---------------------------------|
| **Frontend**    | Streamlit, HTML, CSS, JavaScript |
| **Backend**     | Python |
| **Database**    | MySQL |
| **Modules**      | pandas, pyresparser, pdfminer3, Plotly, NLTK |

---

## ✨ Key Features

### 🧑‍💻 Applicant Features

- **Automatic Resume Parsing**  
  Extracts:
  - Personal Information
  - Key Skills
  - Keywords

- **Smart Recommendations**  
  Provides:
  - Suggested Skills to Add
  - Predicted Job Roles
  - Recommended Courses & Certifications
  - Resume Improvement Tips
  - Overall Resume Score
  - Curated Interview & Resume Tips Videos

---

### 🧑‍💼 Admin Dashboard

- **Manage All Applicant Data**  
  - View data in a user-friendly table
  - Download data as CSV
  - Access uploaded resumes directly
  - View user feedback & ratings

- **Visual Insights**  
  Interactive **Pie Charts** for:
  - User Ratings
  - Predicted Job Fields / Roles
  - Experience Levels
  - Resume Scores
  - User Count (Overall & Location-based: City, State, Country)

---

### 📝 Feedback System

- Collect and track user feedback
- 5-star rating system
- View **overall rating breakdown** with pie charts
- Access **user comments history** for continuous improvement

---

## 📋 Requirements

Make sure the following are installed for smooth setup:

1. **Python 3.9.12** ➡️ [Download Python](https://www.python.org/downloads/release/python-3912/)
2. **MySQL Server** ➡️ [Download MySQL](https://www.mysql.com/downloads/)
3. **Visual Studio Code** (Recommended IDE) ➡️ [Download VS Code](https://code.visualstudio.com/Download)
4. **Visual Studio Build Tools for C++** ➡️ [Download Build Tools](https://aka.ms/vs/17/release/vs_BuildTools.exe)

---

## ⚙️ Setup & Installation Guide

### Clone the Repository

```bash
git clone https://github.com/deepakpadhi986/AI-Resume-Analyzer.git
```

### Create & Activate Virtual Environment

```bash
cd AI-Resume-Analyzer

# Create virtual environment
python -m venv venvapp

# Activate virtual environment
cd venvapp/Scripts
activate
```

### Install Dependencies

```bash
# Navigate back to App directory
cd ../../App

# Install required packages
pip install -r requirements.txt

# Download NLP Model
python -m spacy download en_core_web_sm
```

### Database Setup

- Create a **MySQL Database** named:  
    ```cv```

- Update your MySQL **user credentials** inside ```App.py```:
[App.py Line 92] (https://github.com/asynchronousani/Resume-Analyzer-using-NLP/blob/main/App/App.py#L92)

---

### Running the Application

Ensure the virtual environment is activated and your working directory is inside `App`.

```bash
streamlit run App.py
```

---

## **Contributing 🤝:**
Contributions to the project are welcome! Whether it's improving the model's performance, adding new features, or optimizing the code, feel free to submit pull requests.

---
