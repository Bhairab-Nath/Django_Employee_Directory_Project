# 🧑‍💼 My First Django Project — Employee Directory

This is my **first Django web application**, built to understand the **MVT (Model-View-Template)** pattern and how Django handles databases, templates, and URLs.  
It’s a simple **Employee Directory System** that displays employee details and shows how data flows in a Django project.

---

## 🧠 What I Learned

Through this project, I learned about:
- Django **MVT architecture**
- How to create **models**, **views**, and **templates**
- Mapping **URLs** and handling **HTTP responses**
- Serving **static** and **media** files
- Using Django ORM for **database operations**
- Running **migrations** and managing data in `db.sqlite3`

---

## ⚙️ Features

✅ Employee list shown in a table  
✅ Employee detail page (full info view)  
✅ Fetching data from database  
✅ Use of Django templates for dynamic HTML pages  
✅ Basic use of static and media files  

---

## 🧩 Project Setup

### 1. Clone the Repository
```bash

git clone https://github.com/Bhairab-Nath/Django_Employee_Directory_Project.git

```

### 2. Create Virtual Environment & Activate
```bash

python -m venv env
source env/Scripts/activate        # For Windows using Git bash
# or
source env/bin/activate     # For Mac/Linux

```

### 3. Install Dependencies
```bash

pip install -r requirements.txt

```
### 4. Create media Folder (for uploaded files)
- Create a media folder in root directory-
 used to save media uploaded by user. 

### 5. Apply Migrations
```bash

python manage.py makemigrations
python manage.py migrate

```

### 6. Create Superuser (for Admin Panel)
```bash

python manage.py createsuperuser

```

### 7.Run Server
```bash

python manage.py runserver

```

### 8. Access the App

🌐 Open: http://127.0.0.1:8000/
🔑 Admin Panel: http://127.0.0.1:8000/admin/
