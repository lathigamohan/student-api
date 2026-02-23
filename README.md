# **Student API**  
A simple REST API to manage students using **FastAPI** and **SQLite**.

---

## **Tech Stack**  
- **Python:** 3.13  
- **Framework:** FastAPI  
- **Database:** SQLite  
- **Server:** Uvicorn  

---
Open http://127.0.0.1:8000/docs
 to try out the API.
 
## **How to Run**  
```bash
git clone https://github.com/lathigamohan/student-api.git
cd student-api
python -m venv venv

# Activate virtual environment
# Windows:
.\venv\Scripts\Activate.ps1
# Linux/Mac:
source venv/bin/activate

pip install -r requirements.txt
uvicorn main:app --reload
