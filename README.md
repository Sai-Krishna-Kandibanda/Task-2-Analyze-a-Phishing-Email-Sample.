# Task-2-Analyze-a-Phishing-Email-Sample.
Phishing Email Analysis – Microsoft Phishing Example

## Objective
The objective of this task is to analyze a phishing email sample to identify typical phishing characteristics such as domain spoofing, suspicious links, social engineering through urgency, and email header anomalies. This helps build awareness of phishing tactics and improves skills in detecting and defending against such cyber threats.

## What is Phishing?
Phishing is a type of cyberattack where criminals pretend to be trustworthy sources to trick you into revealing sensitive info or clicking malicious links.

## Types of Phishing
- **Email Phishing (current example)**
- Spear Phishing
- Whaling
- Smishing (SMS phishing)
- Vishing (voice phishing)
- Clone Phishing

## The Attack I Analysed
This is an **Email Phishing** attack using typosquatting. The domain and email use “micr0soft” (with a zero) instead of “microsoft”, impersonating Microsoft Security Team to trick the recipient into clicking a malicious link.

## Tools Used
- MXToolbox Email Header Analyzer (https://mxtoolbox.com/EmailHeaders.aspx) to check SPF/DKIM/DMARC results.
- Screenshot tools (Snipping Tool) for capturing evidence.
- Notepad for text files.

## Step-by-Step Analysis
- **Sender’s Email:**  
   The sender is `account-security@micr0soft-support.com`. The “micr0soft” domain uses a zero instead of “o,” a classic typosquatting tactic.
- **Header Analysis:**  
   I Took sample headers and analysed them with MXToolbox. Found SPF fails, no DKIM/DMARC records found, and sending server is not Microsoft (see included file `header-analysis.txt`). 
- **Urgent Language:**  
   Message pressures to act quickly or risk account suspension. The email warns of “unusual sign-in activity” and threatens account suspension within 24 hours to pressure quick action.
- **Generic Greeting:**  
   Uses “Dear User” instead of your real name and maintains grammatically correct but generic wording.
- **No Attachments:**  
   No attachments here, but always be cautious of unexpected ones in other cases.
- **Social Engineering:**  
   The email exhibits multiple classic phishing signs domain spoofing, social engineering urgency, suspicious URLs, failed authentication, and generic personalization.
   Uses device/location details to sound convincing.
- **Follow Safety Precautions:**  
   Never click suspicious links, verify suspicious senders independently, and be cautious of urgent requests in unsolicited emails.

## How to Protect ourself from phishing
- Inspect email addresses carefully for subtle misspellings.
- Hover over links to verify real destinations without clicking.
- Don’t rush action, phishers use urgency as a psychological trick.
- Avoid downloading or opening unexpected attachments.
- If unsure, visit official websites directly rather than clicking links.
- Keep software and browsers updated.
- Confirm sensitive requests through official and separate communication channels.
