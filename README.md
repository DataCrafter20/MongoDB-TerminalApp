<h1 align="center">📚 MongoDB-TerminalApp</h1>

<p align="center">
  <b>A powerful, interactive terminal application for managing university student data using MongoDB.</b><br>
  Built with Python. Designed for learning. Crafted for real-world CRUD & aggregation mastery.
</p>

---

## ✨ Why This Project 

This isn’t just another CRUD project — it’s a **full learning toolkit** disguised as a CLI app.  
It includes:

- 🔍 **Smart Searching** and pattern-matching  
- 🧠 **Aggregations that feel like mini-data-science tasks**  
- 🧱 **Clean architecture** (modular, scalable, easy to extend)  
- 🧪 **Realistic university dataset operations**  
- 💡 **Error-handling & input validation made professional**  

---

## 🔥 Special Features (Unique Additions)

### ⭐ 1. Intelligent Querying Engine
- Search by name (partial or full match)  
- Search by student number  
- Case-insensitive pattern matching  
- Returns structured console output  

### ⭐ 2. Data Insights Mode (Premium Feature)
Run advanced aggregation pipelines such as:  
- 📊 *Distribution of students per major*  
- 📈 *Average grade per module*  
- 🏅 *Top 5 performing students*  
- 🧮 *Module enrollment statistics*  

### ⭐ 3. Built-In Data Cleaner
- Removes duplicated data  
- Standardizes field formats  
- Verifies required fields  
- Safely handles missing/invalid values  

### ⭐ 4. Fully Interactive Student Profiles
Supports arrays such as:  
- Modules  
- Majors  
- Results  
- Societies  

And performs:  
- Push / pull operations  
- Updating elements in arrays  
- Filtering inside nested arrays  

### ⭐ 5. Modern CLI Design
- Beautiful separators  
- UPPERCASE sections  
- Consistent formatting  
- Human-friendly output  

---

## 🛠️ Tech Stack

| Component | Technology |
|----------|------------|
| Language | Python 3 |
| Database | MongoDB |
| Driver | PyMongo |
| Interface | Command-line (Text-based UI) |

---

## 🗂️ Project Structure

MongoDB-TerminalApp/
│
├── app.py # Main CLI interface
├── db.py # Database connection layer
├── queries.py # All CRUD + advanced MongoDB operations
├── utils.py # Formatting, validation, helpers
├── README.md # Project documentation
└── requirements.txt # Dependencies



---

## 🚀 Getting Started

### 1️⃣ Clone the repo
```bash
git clone https://github.com/DataCrafter20/MongoDB-TerminalApp.git
cd MongoDB-TerminalApp
2️⃣ Create + activate virtual environment
bash
Copy code
python -m venv venv
source venv/bin/activate      # macOS / Linux
venv\Scripts\activate         # Windows
3️⃣ Install requirements
bash
Copy code
pip install -r requirements.txt
4️⃣ Make sure MongoDB is running
Default URI:

arduino
Copy code
mongodb://localhost:27017/
5️⃣ Launch the app
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
📊 Sample Aggregations Output
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
Want to add cool MongoDB operations?
Want to extend the CLI?
Pull requests are welcome!

📜 License
Released under the MIT License — free to use, modify, and learn from.

👤 Author
DataCrafter20 | Purplerain-design | 
