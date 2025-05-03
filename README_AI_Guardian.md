
# 🛡️ AI Guardian – Real-Time Smart Surveillance System

**AI Guardian** is an intelligent, real-time surveillance and alerting system designed to detect motion and suspicious human activities using computer vision, pose estimation, and alert generation.

---

## 🚀 Features

- 📷 Real-time camera monitoring with live pose tracking
- 🧠 Suspicious activity detection using human pose & motion behavior
- 🗂️ Historical logs of detections with timestamps
- 📊 Dynamic charts for alerts & activity trends
- 📩 Email notifications for admin-configured events
- 📼 Upload video files and run detection
- 🧑‍💻 Admin login panel for system control

---

## 🧠 Technologies Used

- **Python**, **OpenCV**, **TensorFlow**, **MediaPipe**
- **Flask** (Backend and Web UI)
- **HTML5**, **CSS3**, **JavaScript**, **Chart.js**
- **Pose Estimation**, **YOLOv8**, **DeepSORT**
- **Email alert system** (via `smtplib`)
- **CSV logging** for alerts and detection stats

---

## 🖥️ Screenshots

### Real-Time Surveillance
![Screenshot](Screenshot 2025-05-03 at 11.01.35 PM.png)

### Detection Statistics & Alerts
![Screenshot](Screenshot 2025-05-03 at 11.02.14 PM.png)

### Detection History Table
![Screenshot](Screenshot 2025-05-03 at 11.02.31 PM.png)

### Detection Growth Chart
![Screenshot](Screenshot 2025-05-03 at 11.02.42 PM.png)

### Suspicious Activity Trend
![Screenshot](Screenshot 2025-05-03 at 11.02.55 PM.png)

### Video Upload Interface
![Screenshot](Screenshot 2025-05-03 at 11.03.46 PM.png)

### Detection Visualization on Video
![Screenshot](Screenshot 2025-05-03 at 11.04.05 PM.png)

---

## 🧑‍💻 Authors

- **Abhinesh Singh**  
- **Sudhansu Sahu**

---

## 📦 Setup Instructions

1. Clone the repository  
   `git clone https://github.com/your-repo/ai_guardian.git`

2. Create a virtual environment and activate it  
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # macOS/Linux
   venv\Scripts\activate     # Windows
   ```

3. Install required packages  
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application  
   ```bash
   cd src
   python app.py
   ```

5. Open in browser  
   Visit `http://127.0.0.1:5000`

---

> 🔒 This is a prototype system for educational and R&D purposes. Do not deploy in critical infrastructure without security validation.
