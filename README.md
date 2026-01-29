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
