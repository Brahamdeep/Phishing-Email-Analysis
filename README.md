# 📧 Phishing Email Analysis Report

This project contains a detailed analysis of a sample phishing email. The goal is to identify key phishing indicators and document them in a structured PDF report.

## 🧾 Overview

The report walks through:
- Sender email spoofing
- Header analysis using online tools
- Suspicious links and URLs
- Use of urgency and fear tactics
- Spelling/grammar issues
- Brand impersonation indicators

The final PDF serves as a sample template for email forensics or cybersecurity coursework.

## 📂 Contents

- `Phishing_Email_Analysis_Report.pdf` — Final report with annotated phishing indicators.
- `email_sample.txt` *(optional)* — The phishing email used for analysis.
- `generate_report.py` — Python script using FPDF to generate the report.

## 🛠 Tools Used

- [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- [VirusTotal](https://www.virustotal.com/)
- [PhishTank](https://www.phishtank.com/)
- [FPDF](https://pyfpdf.github.io/)

## 🧑‍💻 Usage

Clone the repo and run the script to generate the PDF:

```
git clone https://github.com/yourusername/phishing-analysis.git
cd phishing-analysis
python generate_report.py
