# 🛡️ Phishing Email Analysis Report

## 🧾 Email Summary

**Subject:** URGENT: Your Account Has Been Limited!  
**Sender:** PayPal Support <support@paypall.com>  
**Recipient:** user@example.com  
**Date:** (Not specified in sample)  
**Link Provided:** http://paypal-security-update.tk/login

---

## 🔍 Indicators of Phishing

| Indicator | Description |
|----------|-------------|
| **Fake Domain Name** | The sender's email is `support@paypall.com`, which contains an extra "l". This is a spoofed domain attempting to impersonate PayPal. |
| **Urgency and Threat Language** | The message includes phrases like “Your account has been limited” and “verify within 24 hours or it will be permanently suspended.” This is a classic social engineering tactic to pressure the user. |
| **Suspicious Link** | The URL provided (`http://paypal-security-update.tk`) is not a valid PayPal domain. The `.tk` TLD is commonly used in phishing scams. Hovering over the link (in a real email client) would show it differs from the visible text. |
| **Generic Greeting** | The email starts with “Dear Customer” instead of addressing the recipient by their real name, indicating a mass phishing attempt. |
| **Grammar Errors** | Sentences like “Please verify your informations” contain grammar issues, which are common in phishing emails. |
| **Lack of Personalization or Account Info** | Legitimate service emails usually include your name, last 4 digits of your account, or part of your email address. This email lacks all of that. |
| **Spoofed Email Header (Expected)** | While we don't have the raw headers in this sample, phishing emails often have mismatched `From` and `Return-Path` headers when analyzed with tools like MXToolbox. |

---

## 🔬 Suggested Tools for Verification

- **Email Header Analyzer**: [https://mxtoolbox.com/EmailHeaders.aspx](https://mxtoolbox.com/EmailHeaders.aspx)
- **Link Scanner**: [https://www.virustotal.com/](https://www.virustotal.com/)
- **Phishing Database Check**: [https://phishcheck.me/](https://phishcheck.me/)

---

## 🚨 Conclusion

This email is a **clear phishing attempt** designed to steal login credentials by impersonating PayPal. The combination of urgency, suspicious domain, fake sender, and grammar issues indicate it's not legitimate.

**Recommendation:**  
Do not click on the links. Report the email to your email provider or PayPal directly, and educate users on how to recognize these threats.

---

## ✅ Actions Taken

- Phishing email saved for documentation
- Report created and submitted
- Awareness spread to peers

