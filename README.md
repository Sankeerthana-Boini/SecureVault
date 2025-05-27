# 🔐 SecureVault

SecureVault is an enterprise-grade **Data Leakage Prevention (DLP)** system built in Python. It protects sensitive information from being leaked via files, clipboard, USB, emails, or network by using real-time monitoring, pattern matching, and machine learning.

---

## 🚀 Features

- ✅ Real-time file, clipboard, email, USB, and network monitoring  
- 🔍 Regex and keyword-based PII detection  
- 🤖 ML/NLP-based file classification  
- 🔐 Role-based security policy engine  
- 🚨 Alerting system and audit logging  
- 📊 PDF and CSV reporting  
- 🖥️ GUI dashboard using Tkinter  

---

## 🛠️ Tech Stack

- **Language**: Python 3.x  
- **Monitoring**:  
  - `watchdog` (Filesystem)  
  - `pyperclip` (Clipboard)  
  - `psutil` (System/USB detection)  
  - `pyshark` (Packet capture)  
- **ML/NLP**: `scikit-learn`, `spaCy`, `NLTK`  
- **Storage**: SQLite or PostgreSQL  
- **GUI**: Tkinter (optional)  
- **Reporting**: `fpdf`, `matplotlib`, `csv`  
- **Security**: `pycryptodome`  
- **Alerting**: Gmail SMTP, Telegram, Slack Webhooks  

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/SecureVault.git
cd SecureVault

##  Install Dependencies

pip install -r requirements.txt


## Run Individual Modules

python core/email_monitor.py
python core/usb_monitor.py
python core/clipboard_monitor.py
python core/file_monitor.py
python core/network_monitor.py
python reporting/report_generator.py

## Run Main Application
python main.py

## 📊 ML Model Info

Vectorizer: TF-IDF

Classifier: Logistic Regression / LSTM

Accuracy: 92.3%

Recall: 93.5%

Precision: 89.1%

## 🧾 PDF Report Output Includes:
📋 Summary of alerts

📁 Activity logs

📈 Risk trend charts

🔐 Sensitive file classification results

## ⚠️ Known Issues
USB write blocking may not be supported on all platforms

pyshark requires administrative privileges

Email alerts limited to Gmail with OAuth2 or SMTP-auth


## 📚 Learning Outcomes
Real-time system/network programming in Python

Regex and NLP-based PII detection

ML-based file classification

PDF/CSV reporting and GUI integration

##  📄 License
This project is for educational purposes. See the LICENSE file for usage terms.

##  👥 Contributors
Sankeerthana Boini – Project Lead

## 💡 Feedback & Suggestions
Feel free to open issues or contribute improvements via pull requests.


You can now paste this in your `README.md` file in VS Code. Let me know if you'd like:

- a version specifically for the GUI
- instructions to publish on GitHub
- screenshots or badge integration (build, license, etc.)













