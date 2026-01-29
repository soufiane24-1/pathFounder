# 🚀 PathFounder

**PathFounder** is a fast and lightweight web path scanner written in Python.  
It is designed for **authorized penetration testing only**, allowing you to discover hidden directories and files on a target website using a wordlist.

The tool uses **multithreading** for high performance and displays clean, colored output using the **Rich** library.

---

## ✨ Features

- ⚡ Fast scanning with multithreading
- 🎨 Colored and readable output (Rich)
- 🧠 Smart filtering by **HTTP status code + line count**
- ⏱️ Custom timeout support
- 🧵 Adjustable number of threads
- 🛡️ Custom User-Agent
- 📂 Supports custom wordlists

---

## 📦 Requirements

- Python 3.8 or higher
- Required libraries:

```bash
pip install requests rich
## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/soufiane24-1/pathFounder.git
cd pathFounder
chmod +x pathFounder
./pathFounder -u https://example.com -w wordlist.txt
./pathFounder -u https://example.com -w paths.txt -t 100
./pathFounder -u https://example.com -w paths.txt --timeout 10
./pathFounder -u https://example.com -w paths.txt -f 200:15
