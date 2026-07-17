# 🛡️ Malware Detector

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![YARA](https://img.shields.io/badge/YARA-Detection-red.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

A command-line malware detection tool built with **Python** that performs malware scanning using **YARA rules** and **Office macro analysis**. The project helps identify suspicious files by combining signature-based detection with macro inspection.

---

## 📖 Overview

Malware Detector is designed for cybersecurity enthusiasts, students, and SOC analysts who want to perform quick malware scans on files.

The tool can:

- Detect malware using custom YARA rules
- Analyze Microsoft Office documents for malicious macros
- Display scan results with a clean terminal interface
- Generate quick indicators for suspicious files

---

## ✨ Features

- 🔍 YARA-based malware detection
- 📄 Office document macro analysis
- 🎨 Colorized command-line output
- ⚡ Fast file scanning
- 🛠️ Easy to extend with custom YARA rules
- 💻 Cross-platform (Windows/Linux)

---

## 🛠️ Technologies Used

- Python 3
- YARA
- python-magic
- oletools
- colorama

---

## 📂 Project Structure

```
malware-detector/
│
├── malware_detector/
│   ├── cli.py
│   ├── scanner.py
│   ├── analyzer.py
│   └── utils.py
│
├── rules/
│   └── malware_rules.yar
│
├── requirements.txt
├── setup.py
├── README.md
└── LICENSE
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/malware-detector.git
cd malware-detector
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Install the package

```bash
python setup.py install
```

---

## ▶️ Usage

### Scan a file

```bash
python cli.py path/to/file
```

or

```bash
malware-detector path/to/file
```

Example:

```bash
python cli.py sample.exe
```

---

## 🔎 Detection Process

The application performs the following steps:

1. Validates the input file.
2. Detects the file type.
3. Scans the file using YARA signatures.
4. Performs Office macro analysis (if applicable).
5. Displays scan results.
6. Reports suspicious indicators.

---

## 📦 Dependencies

```
python-magic
oletools
yara-python
colorama
```

---

## 🧪 Example Output

```
----------------------------------------
Malware Detector
----------------------------------------

Scanning: sample.exe

✔ File Loaded Successfully

YARA Scan:
Detected Rule: Trojan.Generic

Macro Analysis:
No malicious macros detected.

Result:
⚠ Suspicious File Detected
```

---

## 🔐 Future Improvements

- GUI version using Tkinter/PyQt
- PDF malware analysis
- PE header analysis
- VirusTotal API integration
- Hash (MD5/SHA256) generation
- IOC extraction
- HTML/PDF scan reports
- Multi-threaded scanning
- Real-time folder monitoring

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Debangshu Kumar**

Cybersecurity Enthusiast | SOC Analyst | Malware Analysis | Threat Hunting

- GitHub: https://github.com/Debangshu-sci
- LinkedIn: https://www.linkedin.com/in/debangshu-sci

---

⭐ If you found this project useful, consider giving it a star on GitHub!
