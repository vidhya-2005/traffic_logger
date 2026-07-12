# 🚦 Smart Traffic Violation Logger

A web-based Traffic Violation Management System developed using **Flask** and **SQLite** that enables authorities to digitally record traffic violations, generate QR-enabled challans, track payment status, and manage violation history efficiently.

---

## 📌 Project Overview

The Smart Traffic Violation Logger replaces traditional paper challans with a digital system. It allows traffic officers to record violations, automatically generate QR codes for each challan, update payment status, and maintain a searchable violation history.

---

## ✨ Features

- 🚔 Add new traffic violations
- 📄 Generate digital challans
- 📱 Automatic QR Code generation
- 🔍 Search violations by vehicle number
- 🎯 Filter by violation type
- ✅ Filter by payment status
- 📅 Sort by latest or oldest records
- 💰 Sort by highest or lowest fine amount
- ✏️ Update payment status (Paid / Unpaid)
- 🌐 Public violation status page
- 💾 SQLite database integration
- 📱 Responsive Bootstrap interface

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- Jinja2 Templates

### Backend
- Python
- Flask
- Flask-SQLAlchemy

### Database
- SQLite

### Libraries
- qrcode
- Pillow

---

## 📂 Project Structure

```
Smart-Traffic-Violation-Logger/
│
├── app.py
├── requirements.txt
├── traffic.db
│
├── templates/
│   ├── base.html
│   ├── home.html
│   ├── add_violation.html
│   ├── history.html
│   ├── update_status.html
│   ├── challan.html
│   └── public_status.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   └── qr_codes/
│
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/Smart-Traffic-Violation-Logger.git
```

```bash
cd Smart-Traffic-Violation-Logger
```

---

### 2️⃣ Create Virtual Environment (Optional)

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux/Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run the Application

```bash
python app.py
```

---

### 5️⃣ Open in Browser

```
http://127.0.0.1:5000/
```

---

## 📖 How It Works

1. Open the application.
2. Add a new traffic violation.
3. Enter:
   - Vehicle Number
   - Violation Type
   - Location
   - Date
   - Fine Amount
4. Submit the form.
5. The system:
   - Stores the violation in SQLite
   - Generates a QR Code
   - Creates a Digital Challan
6. Users can:
   - View challan
   - Check payment status
   - Update payment status
   - Filter and search records

---

## 📸 Screenshots

Add screenshots here after running the project.

Example:

```
Home Page

Add Violation Page

Violation History

Digital Challan

QR Code

Public Status Page
```

---

## 📦 Dependencies

```
Flask
Flask-SQLAlchemy
qrcode
Pillow
```

---

## 🔮 Future Enhancements

- User Authentication
- Admin Dashboard
- Online Payment Gateway Integration
- Email & SMS Notifications
- PDF Challan Download
- Vehicle Owner Database Integration
- Analytics Dashboard
- GPS-based Violation Tracking
- Camera-based Number Plate Recognition
- REST API Support
- Cloud Database Integration

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Flask Web Development
- CRUD Operations
- SQLite Database Management
- SQLAlchemy ORM
- QR Code Generation
- Dynamic HTML Templates (Jinja2)
- Routing in Flask
- Bootstrap UI Design
- Traffic Record Management System Design

---

## 👩‍💻 Author

**Vidhya Vinothkumar**

- 🎓 B.Tech Information Technology
- 📍 Vivekanandha College of Technology for Women
- 💼 Aspiring Data Analyst | Python Developer
- 🔗 GitHub: https://github.com/vidhya-2005
- 🔗 LinkedIn: https://www.linkedin.com/in/vidhya2005/

---

## 📄 License

This project is developed for educational and academic purposes.

Feel free to use and modify it for learning.

---

⭐ If you found this project useful, consider giving it a Star on GitHub!
