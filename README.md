# 💼 Skill-Based Job Recommendation System

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20Application-red?style=for-the-badge&logo=streamlit)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

### 🚀 AI-Powered Career Guidance & Job Recommendation Platform

Recommend jobs, identify skill gaps, and generate personalized learning paths based on user skills.

</div>

---

# 📌 Overview

The **Skill-Based Job Recommendation System** is a Machine Learning-powered web application that recommends suitable job roles based on a user's existing skills.

The platform analyzes user skills, identifies missing competencies required for target roles, and provides personalized learning recommendations to help users achieve their career goals.

---

# 🎯 Objectives

- Recommend jobs based on current skills
- Perform skill gap analysis
- Suggest personalized learning paths
- Improve career planning and decision-making
- Help students and professionals upskill efficiently

---

# 🚀 Features

✅ Job recommendations based on skills

✅ Skill gap analysis

✅ Personalized learning roadmap

✅ Course recommendations

✅ Career guidance support

✅ Interactive Streamlit interface

✅ Real-time predictions

---

# 🧠 Machine Learning Workflow

```text
User Skills Input
        │
        ▼
Skill Vectorization
(MultiLabelBinarizer)
        │
        ▼
KMeans Clustering
        │
        ▼
KNN Recommendation Engine
        │
        ▼
Job Recommendation
        │
        ▼
Skill Gap Analysis
        │
        ▼
Learning Path Generation
```

---

# ⚙️ Technologies Used

| Category | Technology |
|-----------|------------|
| Language | Python |
| Machine Learning | Scikit-Learn |
| Frontend | Streamlit |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib |
| Dataset Format | CSV |
| Development Platform | Google Colab |

---

# 🧩 Machine Learning Models

## 🔹 MultiLabelBinarizer

Used to convert user skills into machine-readable binary vectors.

### Example

```python
Python, SQL, Excel
```

becomes

```python
[1,0,1,1,0,0]
```

---

## 🔹 KMeans Clustering

Groups similar job roles based on required skillsets.

Purpose:
- Create job clusters
- Improve recommendation quality

---

## 🔹 K-Nearest Neighbors (KNN)

Used to recommend jobs closest to the user's skill profile.

Purpose:
- Find most relevant job roles
- Calculate similarity between users and job requirements

---

# 📂 Dataset

The system uses structured CSV datasets containing:

### Job Dataset

- Job Role
- Required Skills
- Industry
- Skill Requirements

### Learning Resources Dataset

- Skill Name
- Course Title
- Learning Platform
- Course Link

---

# 📊 System Outputs

The application provides:

### Job Recommendations

```text
Data Analyst
Machine Learning Engineer
Business Analyst
Data Scientist
```

### Skill Gap Analysis

```text
Missing Skills:
- SQL
- Power BI
- Statistics
```

### Learning Recommendations

```text
SQL → SQL for Data Science
Power BI → Microsoft Power BI Fundamentals
Statistics → Statistics for Data Science
```

---

# 📁 Project Structure

```text
Skill-Based-Job-Recommendation-System
│
├── datasets/
│   ├── job_skills_dataset_corrected.csv
│   ├── learning_resources_dataset.csv
│
├── app.py
│
├── model/
│
├── requirements.txt
│
├── README.md
│
└── assets/
```

---

# ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Skill-Based-Job-Recommendation-System.git

cd Skill-Based-Job-Recommendation-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

---

# 🌟 Real-World Applications

- Career Guidance Platforms
- Student Placement Systems
- Skill Assessment Platforms
- Learning Recommendation Systems
- EdTech Applications
- Workforce Development

---

# 🔮 Future Enhancements

- Resume Analysis
- AI Career Chatbot
- LinkedIn Profile Integration
- Salary Prediction
- Job Market Trend Analysis
- Generative AI Career Advisor

---

# 👨‍💻 Author

### Prateek Raj

B.Tech CSE (AI & ML)

Manav Rachna University

📧 prateekraj9507@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/prateek-raj-8177a4276/


---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---
