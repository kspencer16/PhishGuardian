# 🐟 PhishGuardian 🐟
PhishGuardian is a web-based phishing detection too that allows users to submit a URL and receive an assessment indicating whether the website may be a phishing scam. This application uses Python to inspect links for common phishing indicators and presents the results through a website built with HTML, CSS, and JavaScript.

# 💻 How it Works 💻
When a user enters a URL into the website:
1. The URL gets sent to the Python backend.
2. The backend performs a series of security checks.
3. Phishing indicators are checked for and analyzed.
4. A risk score is generated.
5. Results are then displayed to the user.

# ✅ What security checks are performed? ✅
  - URL validation
  - Domain age vertification
  - SSL certificate inspection
  - URL length analysis
  - Suspicious keyword detection
  - Detection of URL shortening service
  - IP address usage detection
  - Domain reputation lookup

# ⚠️ Disclaimer ⚠️
This project is intended for educational, research, and cybersecurity awareness purposes. While the system can identify many common phishing indicators, it cannot guarantee the detection of every malicious website. Users should always exercise caution when interacting with unfamiliar websites.
