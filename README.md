Bro 👍 got you.
Here is a **clean, professional `README.md`** you can directly put in your project root.
It is **final-year / GitHub / viva ready**.

---

# 🦷 AI Oral Health Screening System (YOLO-Based)

An AI-powered web application for **oral health screening** using **YOLO deep learning**, which analyzes dental images (Upper, Front, Lower teeth), detects dental conditions, and generates an automated **PDF report** with email delivery.

---

## 📌 Features

* 📷 **Camera-based image capture** (Upper / Front / Lower teeth)
* 🤖 **YOLO deep learning model** for dental condition detection
* 🟩 **Bounding box visualization** on detected teeth
* 📄 **Automatic PDF report generation**
* 📧 **Email delivery of report**
* 🌐 **Flask web application**
* 🧪 Confidence-based prediction output

---

## 🧠 Technologies Used

* **Python 3.10**
* **Flask** – Web framework
* **YOLO (Ultralytics)** – Object detection
* **OpenCV** – Image processing
* **ReportLab** – PDF generation
* **HTML / CSS / JavaScript** – Frontend
* **SMTP (Gmail)** – Email sending

---

## 📂 Project Structure

```
AI-Oral-Health/
│
├── app.py
├── ai_model.py
├── mail_sender.py
├── report_generator.py
├── suggestions.py
├── requirements.txt
│
├── model/
│   └── teeth_yolo.pt
│
├── templates/
│   ├── start.html
│   ├── details.html
│   ├── capture.html
│   └── result.html
│
├── static/
│   ├── uploads/
│   │   ├── upper.jpg
│   │   ├── front.jpg
│   │   └── lower.jpg
│   │
│   └── reports/
│       ├── upper_yolo.jpg
│       ├── front_yolo.jpg
│       ├── lower_yolo.jpg
│       └── Patient_Dental_Report.pdf
│
└── README.md
```

---

## 🚀 How It Works

1. User enters details (Name, Age, Gender, Phone)
2. Captures **Upper, Front, and Lower teeth images**
3. YOLO model detects dental conditions
4. Bounding boxes are drawn on images
5. Final disease & confidence are calculated
6. PDF report is generated
7. Report is sent via email
8. Results are displayed on the web page

---

## ▶️ How to Run the Project

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 2️⃣ Run the Application

```bash
python app.py
```

### 3️⃣ Open in Browser

```
http://127.0.0.1:5000
```

---

## 📧 Email Configuration

Update `mail_sender.py`:

```python
EMAIL = "yourgmail@gmail.com"
PASSWORD = "your_gmail_app_password"
```

> ⚠️ Use **Gmail App Password**, not your normal password.

---

## 📊 YOLO Model

* Model: `teeth_yolo.pt`
* Framework: Ultralytics YOLO
* Purpose: Dental condition detection (caries, stains, malalignment, etc.)

---

## 🎓 Viva Explanation (Short)

> “This system uses a YOLO-based deep learning model to analyze dental images captured through a web interface. The model detects oral health conditions, highlights affected regions using bounding boxes, generates a diagnostic report, and sends it automatically via email.”

---

## ✅ Advantages

* Fast and automated diagnosis
* No manual report preparation
* Visual interpretation using bounding boxes
* Useful for preliminary oral screening

---

## ⚠️ Disclaimer

This application is intended for **educational and screening purposes only** and should **not replace professional dental diagnosis**.



