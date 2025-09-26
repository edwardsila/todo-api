# ✅ To-Do List API  

An easy-to-use **CRUD API** built with **FastAPI**, allowing users to **create, read, update, and delete** to-do tasks.  
Perfect as a beginner-friendly project and a stepping stone for mastering backend development 🚀  

---

## 🌟 Features  
- Create, read, update, and delete tasks  
- Fast and lightweight (built on **FastAPI**)  
- Interactive API docs via Swagger & ReDoc  
- Simple in-memory storage (extendable to a real DB)  

---

## 🛠️ Tech Stack  
- FastAPI – API framework  
- Uvicorn – ASGI server  
- Pydantic – Data validation  

---

## 🚀 Quick Start  

Clone the repo:  
```bash
git clone https://github.com/edwardsila/todo-api.git
cd todo-api
```
Create a virtual environment & install dependencies:
```bash
python3 -m venv venv
source venv\Scripts\activate # Linux/Mac
# or venv\Scripts\activate # Windows

pip install -r requirments.txt
```
Run the API:
```bash
uvicorn main:app --reload
```
Visit:
```bash
http://127.0.0.1:8000/docs
```
