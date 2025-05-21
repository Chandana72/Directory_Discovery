# 🕵️ Hidden Directory Finder (Python)

A simple and effective **Python tool** for discovering hidden directories and endpoints on a target web server. This project is built for **ethical hacking** and **web penetration testing**.

---

## ⚠️ Disclaimer

> This tool is intended for **educational purposes** and **authorized testing only**.  
> Do **not** use this tool without proper permission from the system owner.

---

## 🔍 What It Does

The script performs **directory brute-forcing** by:
- Taking a base URL and a wordlist file containing potential directory names.
- Sending HTTP requests to each possible path.
- Logging and printing discovered (i.e., valid) directories.

---

## 🛠️ Requirements

- Python 3.x
- `requests` library

Install the required library:

```bash
pip install requests
````

---

## 🚀 Usage

```bash
python hidden_directory_finder.py
```

**You will be prompted to enter:**

* `[*] Enter Target URL:` e.g., `example.com`
* `[*] Enter Name Of The File Containing Directories:` e.g., `common.txt`

---

## 🧪 Example

```
[*] Enter Target URL: example.com
[*] Enter Name Of The File Containing Directories: dirs.txt
[*] Discovered Directory At This Path: http://example.com/admin
[*] Discovered Directory At This Path: http://example.com/uploads
```

---

## 📁 Project Structure

```
.
├── hidden_directory_finder.py   # Main script
├── dirs.txt                     # Sample wordlist (not included)
└── README.md
```

---

## 📜 License

MIT License — free to use for educational and authorized purposes.

---

## 👨‍💻 Author

* \[Daniyal Khan]
* [GitHub Profile](https://github.com/ceodaniyal)

---

