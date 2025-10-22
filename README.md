# Task N0 2- Phishing Analysis: Investigating a Phishing Email

## Overview
Analyze a suspicious email to identify phishing characteristics and document your findings. This lab enhances awareness of phishing tactics and email threat analysis skills.

## Objective
Identify phishing characteristics in a suspicious email sample.

## Tools Needed
- Email client or saved email file (plain text)
- Free online header analyzer (e.g., [MXToolbox](https://mxtoolbox.com/EmailHeaders.aspx))

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

## Repository Structure

```
analysis/         # Email samples and scripts
screenshots/      # Images of headers, links, email body, etc.
report.md         # Your analysis and findings
resources/        # Helpful references and tools
```

## Setup Instructions

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Rushikesh38-bit/phishing-analysis-task2.git
    cd phishing-analysis-task2
    ```

2. **Prepare your environment:**
    - Save suspicious email samples in the `analysis/` folder.
    - Store screenshots in `screenshots/`.
    - Write your findings in `report.md`.

## Example Screenshot

![Sample Header Analysis](screenshots/sample-header.png)

## Author
Rushikesh38-bit

## License
MIT

## References
- [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- [Phishing Indicators Guide](https://www.phishing.org/what-is-phishing)
- [Original inspiration repository](https://github.com/BecomingCyber/phishing-lab-day22)
