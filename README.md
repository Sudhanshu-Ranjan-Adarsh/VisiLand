# VisiLand
# 🚀 VisiTrack - AI-Powered Attendance Management System

VisiTrack ek modern, web-based facial recognition attendance system hai. Yeh manual attendance aur proxy marking ki problem ko khatam karne ke liye banaya gaya hai. Isme OpenCV aur Flask ka use karke real-time face detection aur automated record keeping ki suvidha milti hai.

---

## 🌟 Key Features

- *Real-Time Face Recognition:* OpenCV aur Deep Learning models ka use karke instant recognition.
- *Modern Landing Page:* Glassmorphism UI ke saath responsive design (HTML/CSS/JS).
- *Mobile Optimized:* Hamburger menu aur sliding sidebar ke saath fully responsive layouts.
- *Anti-Spoofing:* Liveness detection checks taaki photos ya videos se proxy na lag sake.
- *Automated Analytics:* Attendance records ko CSV/Excel format mein export karne ki suvidha.
- *QR Integration:* Mobile assistant app se sync karne ke liye secure QR authentication.

---

## 🛠️ Tech Stack

### *Frontend:*
* *HTML5 & CSS3:* Semantics aur modern styling (Flexbox/Grid).
* *JavaScript (ES6+):* Dynamic animations aur sidebar toggle logic.
* *Font Awesome:* Tech-centric icons ke liye.
* *Google Fonts:* Clean 'Inter' typography.

### *Backend:*
* *Python (Flask):* Web server aur logic handling.
* *OpenCV:* Image processing aur face detection.
* *NumPy/Pandas:* Data manipulation aur report generation.

---

## 📁 Project Structure

```text
VisiTrack/
├── static/
│   ├── css/         # Desktop & Mobile styles
│   ├── js/          # Scroll animations & Menu logic
│   └── images/      # Product screenshots & QR code
├── templates/
│   └── index.html   # Main Landing Page
├── app.py           # Flask Backend server
├── training/        # Face recognition training data
├── attendance.csv   # Generated attendance records
└── README.md        # Project documentation
