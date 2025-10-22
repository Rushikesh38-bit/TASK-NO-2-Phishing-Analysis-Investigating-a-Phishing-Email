# Task N0 2- Phishing Analysis: Investigating a Phishing Email

## Overview
Analyze a suspicious email to identify phishing characteristics and document your findings. This lab enhances awareness of phishing tactics and email threat analysis skills.

## Objective
Identify phishing characteristics in a suspicious email sample.

## Lab Setup

- 📨 [Download Email Sample (.eml)](https://github.com/0xrajneesh/30-Days-SOC-Challenge-Beginner/blob/main/BRADESCO%20LIVELO.eml)  
- 💻 Tools Recommended:
  - [MX Toolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
  - [EML Analyzer](https://eml-analyzer.herokuapp.com/#/)
  - IP reputation check (e.g., VirusTotal, AbuseIPDB, Cisco Talos)
  - Whois lookup (e.g., whois.domaintools.com)
  - URL and Domain analysis (e.g., urlscan.io, VirusTotal)



## Deliverables
A report listing phishing indicators found in the sample email.

## Mini Guide

1. **Obtain a Sample:**  
   Find a phishing email sample (many are available online).

2. **Sender Spoofing:**  
   Examine the sender’s email address for signs of spoofing.

3. **Header Analysis:**  
   Check email headers for discrepancies using an online header analyzer.

4. **Suspicious Content:**  
   Identify suspicious links or attachments.

5. **Language:**  
   Look for urgent or threatening wording in the email body.

6. **URL Mismatch:**  
   Hover over links to check for mismatched URLs.

7. **Errors:**  
   Verify presence of spelling or grammar mistakes.

8. **Summary:**  
   List and summarize all phishing indicators you find.


## Example Screenshot

![Sample Header Analysis](screenshots/sample-header.png)

## Author
Rushikesh38-bit

## Learning Outcome

By completing this lab, I was able to:
- Extract and review email headers for spoofing and IP trace
- Detect suspicious sending domains and malformed headers
- Identify spoofed branding and urgency in email body
- Use online tools to validate IP/domain reputation and catch phishing attempts


## References
- [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- [Phishing Indicators Guide](https://www.phishing.org/what-is-phishing)
- [Original inspiration repository](https://github.com/BecomingCyber/phishing-lab-day22)
