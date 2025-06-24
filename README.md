# 📧 Internship Task 2 – Phishing Email Analysis

## 🎯 Objective

The goal of this task is to analyze a suspicious email for common phishing indicators and understand how to detect potential email-based threats using basic inspection techniques.

---

## 📥 Email Sample

A suspicious email claiming to be from PayPal was analyzed.  
You can view the sample in:  
📄 `phishing_email_sample.txt`

---

## 🕵️‍♂️ Key Phishing Indicators Found

| Indicator                | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| **Fake Sender Address**  | `support@paypall.com` – extra "l" in PayPal domain                          |
| **Urgent Language**      | Threatens account suspension within 24 hours                                |
| **Suspicious Link**      | `http://paypal-security-update.tk` – not an official PayPal domain         |
| **Generic Greeting**     | Uses “Dear Customer” instead of user's name                                 |
| **Grammar Mistakes**     | Multiple grammar errors like "verify your informations"                     |
| **Lack of Personal Info**| No reference to user details, account ID, or name                           |

📄 See detailed findings in: `analysis_report.md`

---

## 🔧 Tools Used

- MXToolbox Email Header Analyzer  
- VirusTotal URL Scanner  
- Manual inspection (hover-over link checking)

---

## 📁 Files in this Repo

- `phishing_email_sample.txt` – The raw phishing email sample  
- `analysis_report.md` – Detailed analysis report  
- `README.md` – Task summary and documentation

