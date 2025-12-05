<h1 align="center">📚 MongoDB-TerminalApp</h1>

<p align="center">
  <b>A powerful, interactive terminal application for managing university student data using MongoDB.</b><br>
  Built with Python. Designed by three students. Created for real-world CRUD, aggregations, and university-level data management.
</p>

---

## 🏫 Project Overview

**MongoDB-TerminalApp** is an interactive Python terminal program designed by three university students as part of a Computer Science project.  
It manages student information stored in a **MongoDB database**, allowing users to:

- Perform full **CRUD operations**
- Execute **advanced queries** using logical operators
- Manipulate **arrays** (modules, results, societies)
- Run **aggregation pipelines** for insights  
- Work with a **realistic dataset** generated using the *Faker* library

This project offers both **local MongoDB** support and **MongoDB Atlas** cloud support.

---

## ✨ Why This Project:

This isn’t just another CRUD project — it's built as a **learning toolkit** for working with real MongoDB databases.  
It features:

- 🔍 **Smart searching** & intelligent pattern matching  
- 🧠 **Data-insight tools** powered by aggregation pipelines  
- 🧱 **Clean modular architecture**
- 🧪 **Realistic student datasets** (generated with Faker)
- 💡 **Robust error handling and validation**

---

## 🔥 Special Features (Unique Additions)

### ⭐ 1. Intelligent Querying Engine  
- Full/partial name search  
- Search by student number  
- Case-insensitive pattern matching  
- Clean, structured console output  

### ⭐ 2. Data Insights Mode  
Includes professional aggregation pipelines:  
- 📊 Distribution of students per major  
- 📈 Average grade per module  
- 🏅 Top 5 performing students  
- 🧮 Module enrollment statistics  

### ⭐ 3. Built-In Data Cleaner  
- Standardizes field formats  
- Detects & removes duplicates  
- Ensures required fields exist  

### ⭐ 4. Fully Interactive Student Profiles  
Manipulate embedded arrays:  
- Modules  
- Majors  
- Results  
- Societies  

Supports:  
- `$push` / `$pull`  
- Filtering inside arrays  
- Updating nested values  

### ⭐ 5. Modern CLI Interface  
- Beautiful dividers & menus  
- Clean uppercase headings  
- Logical, user-friendly workflow  

---

## 🛠️ Tech Stack

| Component  | Technology |
|-----------|------------|
| Language  | Python 3 |
| Database  | MongoDB |
| Driver    | PyMongo |
| Interface | Terminal / CLI |

---

## 🗂️ Project Structure

MongoDB-TerminalApp/
│
├── app.py # Main CLI interface
├── db.py # Database connection layer
├── queries.py # CRUD + advanced MongoDB operations
├── utils.py # Formatting, validation, helper functions
├── README.md # Project documentation
└── requirements.txt # Dependencies

yaml
Copy code

---

## 🚀 How to Run the App

### **Option 1 — Local MongoDB**

1. Install **MongoDB Community Server** and start the service.
2. Use the default connection string:

client = MongoClient("mongodb://localhost:27017/")

markdown
Copy code

3. Optionally generate a dataset with **Faker**.
4. Create and activate a virtual environment.
5. Install dependencies.
6. Run:

```bash
python app.py
Option 2 — MongoDB Atlas (Cloud)
Create a free MongoDB Atlas account

Create a cluster

Create a university database with a students collection

Replace your local URI with your Atlas URI:

ini
Copy code
client = MongoClient("your_atlas_connection_string_here")
Install dependencies

Run:

bash
Copy code
python app.py
1️⃣ Clone the Repo
bash
Copy code
git clone https://github.com/DataCrafter20/MongoDB-TerminalApp.git
cd MongoDB-TerminalApp
2️⃣ Create + Activate a Virtual Environment
bash
Copy code
python -m venv venv
source venv/bin/activate      # macOS / Linux
venv\Scripts\activate         # Windows
3️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
4️⃣ Ensure MongoDB is Running
Default local URI:

arduino
Copy code
mongodb://localhost:27017/
5️⃣ Launch the App
bash
Copy code
python app.py
🧭 CLI Preview
markdown
Copy code
=========================================
     UNIVERSITY STUDENT DB - TERMINAL
=========================================

1. Add new student
2. View all students
3. Search student
4. Update student profile
5. Delete student
6. Data Insights / Aggregations
7. Data Cleaner (Fix / Standardize)
8. Exit

Choose an option:
📊 Sample Aggregation Output
markdown
Copy code
Major Distribution:
-------------------------
Computer Science     42
Information Systems  31
Mathematics          18
Physics              12
markdown
Copy code
Top 5 Students by Average Grade:
-----------------------------------------
1.   Sarah M.        88.7
2.   Lucas K.        87.5
3.   Aisha T.        85.9
...
🤝 Contributing
Got ideas for improvements?
New MongoDB operations you want to add?
Pull requests are welcome!

📜 License
This project is licensed under the MIT License.

👤 Authors
DataCrafter20
Purplerain-design
