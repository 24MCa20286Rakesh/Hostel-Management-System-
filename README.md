# Hostel Management System (HMS) MVP

**Developed with Python, Flask, and SQLAlchemy ORM.**

---

## 🚀 Parichay (Introduction)

Yeh project ek **Hostel Management System (HMS)** ka **Minimum Viable Product (MVP)** hai. Iska mukhya uddeshya (main goal) **manual aur paper-based** hostel administration process ko **adhunik (modern), Three-Tier web application** se replace karna hai. Is system mein **Data Integrity** aur **Relational Logic** par khaas dhyaan diya gaya hai.

### Mukhya Sidhhi (Core Achievement)

* **Safaltapoorvak (Successfully) C/R (Create & Read) Operational Capability** ko lagu kiya gaya.
* **Single Source of Truth** provide karta hai, jisse data redundancy khatam ho jaati hai.

---

## 🛠️ Technology Stack

Is project ko banane ke liye neeche diye gaye core technologies ka upyog kiya gaya hai:

* **Backend Framework:** Python (Flask Microframework)
* **Database ORM:** Flask-SQLAlchemy (SQLAlchemy)
* **Database Engine:** SQLite3 (Development ke liye)
* **Frontend:** HTML5, CSS3, Jinja2 Templating
* **Dependency Management:** Python venv & `requirements.txt`

---

## ✨ Features (Kya-Kya Karta Hai)

| Category | Functionality | Status |
| :--- | :--- | :--- |
| **Student Management** | New Student Add karna (Create) aur sabhi students ko dekhna (Read). | ✅ Implemented |
| **Room Inventory** | New Room Add karna (Create) aur room inventory dekhna (Read). | ✅ Implemented |
| **Allocation** | Student ko Room ke saath **Foreign Key** se allocate karna aur Allocation ledger dekhna. | ✅ Implemented |
| **Data Integrity** | Null values aur invalid foreign IDs ko database-level par rokna. | ✅ Enforced |

---

## ⚙️ Setup aur Installation (Run Kaise Karein)

Project ko locally run karne ke liye neeche diye gaye steps follow karein.

**1. Repository Clone Karein:**

```bash
git clone [YOUR-REPO-LINK]
cd hostel-management-system
2. Virtual Environment (VENV) Banayein:

Bash

python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate      # Windows
3. Dependencies Install Karein:

Bash

pip install -r requirements.txt
4. Database Banayein aur Application Run Karein:

Bash

python app.py
Application ab https://www.google.com/search?q=http://127.0.0.1:5000/ par chal raha hoga.

🛣️ Future Roadmap (Aage Kya Banega)
Vartamaan mein yeh MVP hai, par iska design future ke bade features ko support karta hai.

a. Phase I (Functional Maturity)

i. Full CRUD: Update aur Delete routes ko jodne ka kaam.

ii. Defensive Programming: Comprehensive Input Validation (Flask-WTF use karke).

b. Phase II (Security Implementation)

i. Authentication: Flask-Login se secure user login/logout system.

ii. Password Hashing: Flask-Bcrypt se passwords ko hash karna.

c. Phase III (Enterprise Features)

i. Attendance Module: QR Code-Based Attendance system ko is database structure ke saath integrate karna.

ii. BI Reporting: Occupancy aur Financial data ke liye advanced reports banana.
