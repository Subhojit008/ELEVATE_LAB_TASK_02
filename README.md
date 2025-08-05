# 📧 Phishing Email Analysis – Cybersecurity Internship Task 2

## 🛡️ Overview

As part of my cybersecurity internship at **Prodigy InfoTech**, this task focuses on analyzing a suspicious phishing email to identify its malicious elements. The objective is to build awareness of phishing techniques and develop skills in detecting email-based threats.

---

## 🎯 Objective

- Identify red flags in a phishing email.
- Analyze technical components like headers, sender details, and URLs.
- Understand common social engineering tactics.
- Improve threat detection and email forensics skills.

---

## 🔍 Analysis Performed

### 1. **Sample Email Collection**
- A publicly available phishing email sample was used for this task.

### 2. **Phishing Indicators Identified**
| Indicator                          | Observation |
|-----------------------------------|-------------|
| **Spoofed Sender Address**        | `support@paypa1.com` instead of `paypal.com` |
| **Urgent/Threatening Language**   | "Your account will be suspended if not verified in 24 hours." |
| **Suspicious URL**                | Hovered link showed `http://fake-paypal-login.com` |
| **Grammar/Spelling Errors**       | Multiple typos and poor grammar |
| **Unexpected Attachment**         | A `.zip` file disguised as "invoice" |
| **Mismatched Display Name/Email** | Display name: "PayPal Support" / Email: `helpdesk@randommail.org` |

### 3. **Header Analysis**
- Used [MxToolbox Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- Found discrepancies in the **Return-Path** and **Received** fields.
- Detected a non-legitimate IP sender address.

---

## 📌 Tools Used

- Email Header Analyzer (MxToolbox / Google Toolbox)
- Web browser for link inspection
- Notepad (for collecting and documenting observations)

---

## 🧠 Key Concepts Learned

- **Phishing**
- **Email Spoofing**
- **Header Forensics**
- **Social Engineering**
- **Cyber Threat Awareness**

---

## 📁 Project Structure

