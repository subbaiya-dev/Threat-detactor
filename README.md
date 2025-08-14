# Threat-detactor
A real-time Android threat detection app that monitors incoming notifications, reads embedded URLs, analyzes their content within seconds, and instantly alerts the user via a warning popup if any malicious or suspicious activity is detected. Designed to enhance user safety with minimal latency and no manual scanning.
# ThreatDetector

ThreatDetector is an Android application built with **Kotlin** and **AI/ML models** to monitor incoming notifications and detect potentially malicious URLs or phishing attempts in real-time.  
The app uses trained machine learning algorithms to analyze links, identify suspicious patterns, and protect users from online threats.

## 🚀 Features
- **AI-Powered Threat Detection** – Uses an ML model to classify URLs as safe, suspicious, or malicious.
- **Real-Time Notification Monitoring** – Intercepts notifications from any app to scan for threats.
- **Phishing & Malware Link Detection** – Detects and flags potentially harmful domains.
- **User Alerts & Details** – Displays detection results with a risk score.
- **Simple UI** – Minimal, user-friendly design for quick decision-making.

## 📂 Project Structure
app/src/main/java/com/example/threatdetector/
├── MainActivity.kt # Main UI and detection logic
├── NotificationListener.kt # Intercepts incoming notifications
├── Threat.kt # Data model for detected threats
├── ThreatAdapter.kt # RecyclerView adapter for displaying results
├── ml/ # (If applicable) ML model files and helper classes
