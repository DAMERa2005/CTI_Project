# 🛡️ CTI Command Center – Dark SOC Dashboard

## 📌 Overview

The **CTI Command Center** is an advanced **Cyber Threat Intelligence Dashboard** that simulates real-time cyber attacks across the globe. It visualizes threat data using interactive charts, geolocation mapping, and live alert feeds.

This project is designed to mimic a **Security Operations Center (SOC)** interface with a modern dark UI, providing insights into cyber threats and attack patterns.



## 🚀 Key Features

### 🌍 Real-Time Attack Simulation

* Simulates global cyber attacks dynamically
* Displays attack locations on an interactive world map (Leaflet)

### ⚠️ Live Alert Feed

* Shows high-risk and critical alerts in real time
* Includes timestamps and attack details

### 📊 Data Visualization

* **Bar Chart:** Attack type distribution (DDoS, Malware, Phishing, etc.)
* **Line Chart:** Threat level trends over time
* Built using Chart.js

### 🔢 Threat Metrics

* Total Attacks
* Active Threats
* Critical Alerts

### 🔊 Audio Alerts

* Sound notifications for high-risk and critical attacks
* Toggle ON/OFF option

### 🎯 Manual Attack Simulation

* Button to trigger test cyber attacks

---

## 🏗️ Technologies Used

* **Frontend:** HTML5, CSS3, JavaScript
* **Libraries:**

  * Leaflet.js (Map Visualization)
  * Chart.js (Data Visualization)
  * Font Awesome (Icons)

---

## 📂 Project Structure

```id="p7u1bx"
CTI_Project/
│
├── index.html      # Main dashboard file
├── README.md       # Documentation
```

---

## ⚙️ How to Run the Project

### ✅ Method 1: Simple (Recommended)

1. Download or clone the repository:

```id="3r1q5l"
git clone https://github.com/yourusername/CTI_Project.git
```

2. Open the folder:

```id="f9g2c2"
cd CTI_Project
```

3. Open `index.html` in browser:

```id="rpl7c6"
Right-click → Open with Browser
```

---

### ✅ Method 2: Using Live Server (VS Code)

1. Install **Live Server extension**
2. Right-click `index.html`
3. Click **"Open with Live Server"**

---

## 📊 How It Works

* Random attacks are generated every few seconds
* Each attack includes:

  * Location (city, country)
  * Attack type
  * Risk score
* High-risk attacks trigger:

  * Alerts
  * Sound notifications
  * UI updates

---

## 🔮 Future Enhancements

* Integration with real-world threat intelligence APIs
* Backend support (Flask / Node.js)
* User authentication system
* Database storage (MySQL / MongoDB)
* AI-based threat prediction

---

## 📷 Screenshots
![alt text](<screenshots/Analytics Dashboard.png>)
![alt text](<screenshots/Alerts Panel.png>)
![alt text](<screenshots/Threat level graph.png>)
![alt text](<screenshots/World Map View.png>)
---

## 🎓 Use Cases

* Cybersecurity academic projects
* SOC dashboard simulation
* Demonstration of threat intelligence concepts
* UI/UX design for security systems

---

## 👩‍💻 Author

**Kattula Susmija**
GitHub: https://github.com/DAMERa2005

---

## 📄 License

This project is for educational and demonstration purposes only.
