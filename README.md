# Cybersecurity-Task-2
📧 Phishing Email Analysis Project
🔍 Overview

This project focuses on identifying phishing characteristics in a suspicious email sample using both content inspection and technical email header analysis. The goal is to understand how phishing attacks operate and how authentication mechanisms help detect spoofed emails.

🎯 Objective

To detect phishing indicators by analyzing:

Email content

Sender details

Embedded links

Attachments

Email authentication results (SPF, DKIM, DMARC)

🛠 Tools Used

Email Client / Saved Email File

Google Admin Toolbox – Message Header Analyzer

Web Browser

🧪 Methodology
1️⃣ Content Analysis

Checked sender email domain

Identified urgency and threat language

Detected generic greetings

Inspected suspicious links

Reviewed attachment types

2️⃣ Header Analysis

Extracted email header and analyzed it using Messageheader Analyzer to verify:

SPF (Sender Policy Framework)

DKIM (DomainKeys Identified Mail)

DMARC (Domain-based Message Authentication)

📊 Findings
Check	Result	Interpretation
SPF	Fail	Unauthorized sender
DKIM	None	No digital signature
DMARC	Fail	Domain authentication failed

The email failed all authentication checks, confirming sender spoofing and phishing characteristics.

🚨 Phishing Indicators Identified

Spoofed sender domain

Urgent call-to-action

Request for sensitive information

Suspicious attachment

Failed authentication protocols

✅ Conclusion

The combined content and technical analysis confirmed that the email was a phishing attempt. This project demonstrates how email authentication mechanisms help detect malicious communications and improve cybersecurity awareness.

📚 Learning Outcomes

Understanding phishing tactics

Practical email header analysis

Identifying spoofed domains

Strengthening cybersecurity fundamentals
