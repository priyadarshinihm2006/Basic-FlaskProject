

# 🚗 Wroom – Web Application

A simple web application built using Flask for the backend and a Bootstrap-powered frontend. Data is managed using SQLite.

---

## 🛠 Technologies Used

* **Frontend**: HTML5, CSS3 (Bootstrap), JavaScript (jQuery)
* **Backend**: Python with Flask
* **Database**: SQLite
* **Version Control**: Git

---

## 🗄️ Setting Up the Database

To create the SQLite database, run the following command in your terminal:

```bash
sqlite3 wroom.db < create_db.sql
```

This will create a `wroom.db` file using the schema defined in `create_db.sql`.

---


## 🚀 Running the Application

To start the Flask application, simply run:

```bash
python3 run.py
```

if it says flask not found or installed, use the below command to install it

```bash
pip3 install flask
```


Then navigate to `http://localhost:8080` in your browser.


---


## 🗄️ Setting Up the Database

To create the SQLite database, run the following command in your terminal:

```bash
sqlite3 wroom.db < create_db.sql
```

This will create a `wroom.db` file using the schema defined in `create_db.sql`.


if sqlite is not present on the machine, try 
```bash
winget install SQLite.SQLite
```

and to get the path

```bash
Get-ChildItem -Path C:\ -Recurse -Filter sqlite3.exe -ErrorAction SilentlyContinue
```

use & 

for example (use your own path)

```bash
& "C:\Users\Pruthviraj Mundargi\sqlite\sqlite3.exe" C:\Guddu\Github\Basic-FlaskProject\dev\wroom.db
```

---






## 📁 Project Structure (optional)

You might consider adding this section if helpful:

```
├── static/
├── templates/
├── create_db.sql
├── run.py
├── wroom.db
├── README.md
```

---
