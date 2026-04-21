# AuthenTrack
# 🔐 AuthenTrack – Face Verification Attendance System

## 📌 Problem

Students events ki wajah se lectures miss karte hain aur baad mein attendance claim karte hain, jo misuse ho sakta hai.

## 💡 Solution

AuthenTrack ek AI-based system hai jo face verification ke through genuine students ko hi attendance deta hai.

## ⚙️ How It Works

1. Student event registration ke time passport size photo upload karta hai
2. Event ke baad attendance form fill karta hai
3. System live photo capture karta hai
4. DeepFace model dono images compare karta hai
5. If similarity score ≥ 70% → Verified
6. If similarity score < 70% → Unverified

## 🧠 Tech Stack

* Python
* OpenCV
* DeepFace
* Flask (if used)

## 🚀 How to Run

```bash
git clone https://github.com/your-username/AuthenTrack.git
cd AuthenTrack
pip install -r requirements.txt
python app.py
```

## 📊 Features

* Face verification based attendance
* Anti-cheating system
* Automated validation

## 🔮 Future Improvements

* Real-time face detection
* Mobile app integration
* Cloud deployment

