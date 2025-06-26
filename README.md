# 🛍️ BuyWise - AI-powered Review Verification

**BuyWise** is a bilingual, AI-enhanced product review platform designed to detect fake reviews in real time, support user trust, and gamify the review ecosystem.

---

## 💡 Project Highlights
- 🧠 **AI Review Verification**: Detect fake reviews using a fine-tuned RoBERTa model.
- 🌍 **Bilingual Interface**: Arabic ↔ English with RTL/LTR support.
- 🎮 **Gamified Engagement**: Points, levels, badges, and redeemable rewards.
- 🔐 **Role-based Access**: Admins, users, and companies.
- 📣 **Real-Time Notifications**: On likes, replies, and reward claims.

---

## 🛠️ Tech Stack
- **Frontend**: HTML, CSS, JS, Bootstrap
- **Backend**: PHP, MySQL
- **AI Model**: Python (RoBERTa), Flask API
- **Tools**: XAMPP, GitHub, HuggingFace, VSCode

---

## 👩‍💻 Team Members
- **Islam Emad Al-Rafati** – Team Leader & Full Stack Development
- **Haneen Maher Ali** – AI Development (RoBERTa, Flask, Dataset)
- **Malak Abdulkareem Zakarneh** – Full Stack Development
- **Raghad Tariq Awwad** – Full Stack Development

---

## 🎥 Demo Video
[▶️ Watch our project walkthrough] https://youtu.be/gpzpg5rX28M?si=gawNSMz4ET5khY13

---

## 📂 Documentation
Full PDF report is available in `/docs/BuyWiseDoc.pdf`.

---

## 📦 How to Run Locally
```bash
# Clone the repo
git clone https://github.com/Aiso03/BuyWise

# Backend - PHP + MySQL (XAMPP)
# Place files in htdocs and import /database/BuyWise.sql

# AI Model - Python Flask API
cd AI/flask_ml_api_code/
pip install -r requirements.txt
python main_custom.py
