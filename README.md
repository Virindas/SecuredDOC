# SecuredDOC: Advanced Cryptographic Document Management System

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

## 📌 Project Overview & Explanation
**SecuredDOC** is a security-centric framework designed to solve the problem of document tampering in digital environments. By utilizing **one-way cryptographic hashing**, the system ensures that once a document is registered, any modification—no matter how small—will result in a hash mismatch, alerting the system to a breach of integrity.

This project was developed as a implementation to demonstrate the practical application of **Applied Cryptography** in a Full-Stack environment (MERN/Python).

## 📄 Project Resources
For a deep dive into the research and logic behind this project, please refer to the following:
* [📂 Technical Report (PDF)](https://github.com/Virindas/SecuredDOC/raw/main/docs/Project_Report.pdf)
* [📊 Project Presentation (PPT)](https://github.com/Virindas/SecuredDOC/raw/main/docs/Project_Presentation.pptx)

## 🚀 Key Technical Features
* **Cryptographic Integrity:** Implements a dedicated `hasher.py` module to handle one-way hashing of sensitive document data.
* **Scalable Backend:** Built with **Flask**, leveraging a modular architecture that separates business logic from data persistence.
* **NoSQL Data Persistence:** Utilizes **MongoDB** for flexible, high-performance storage of document metadata and secure hashes.

## 📂 System Architecture
The project follows a **Modular Monolith** structure:
- `app.py`: The central orchestrator handling routing and API endpoints.
- `hasher.py`: The core security engine implementing cryptographic transformations.
- `database.py`: The Data Access Object (DAO) layer for MongoDB operations.
- `templates/`: A responsive UI layer built for professional user interactions.

## 🛠️ Installation & Setup
1. Clone the repository: `git clone https://github.com/Virindas/SecuredDOC.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Launch the application: `python app.py`

---
**Developer:** Virinda Singh V  
**Specialization:** Computer Science Engineering (Bioscience)  
**Academic Profile:** 9.21 CGPA | SIMATS University
