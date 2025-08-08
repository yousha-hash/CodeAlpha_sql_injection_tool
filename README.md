# 🔍 Bug Bounty Scanner Tool

A **fast, multi-functional security scanning tool** designed for bug bounty hunters, penetration testers, and cybersecurity enthusiasts.  
It helps automate reconnaissance and vulnerability detection by combining **async scanning, subdomain enumeration, and directory brute-forcing** in one package.

---

## ✨ Features

- **Asynchronous Scanning (aiohttp)** – Speeds up HTTP requests by running multiple scans in parallel.
- **Subdomain Enumeration** – Finds hidden subdomains of a target domain.
- **Directory Brute Force** – Detects hidden paths and resources on web servers.
- **Custom Wordlists Support** – Use your own wordlists for fuzzing.
- **Error Handling** – Skips dead hosts and continues scanning.
- **Easy to Extend** – Modular code structure for adding more scanning modules.

---

## 📂 Project Structure

bug_bounty_scanner/
│── scanner.py # Main script
│── subdomains.txt # Wordlist for subdomain scanning
│── directories.txt # Wordlist for directory brute force
│── requirements.txt # Dependencies
└── README.md # Project documentation


## 🛠 Installation

1️⃣ **Clone the repository**
```bash
git clone https://github.com/yourusername/bug-bounty-scanner.git
cd bug-bounty-scanner
2️⃣ Install dependencies
Make sure you have Python 3.8+ installed. Then run:

pip install -r requirements.txt
If pip is not recognized, use:
python -m pip install -r requirements.txt

📌 Usage
Run the scanner with:

python scanner.py -u https://example.com
