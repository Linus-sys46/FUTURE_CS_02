# Phishing Detection & Awareness Project

This repository contains a practical analysis of phishing emails, highlighting how attackers exploit email systems and how users can defend against them. The project demonstrates real-world phishing detection techniques and cybersecurity awareness practices.

---

## Repository Contents

- **Phishing Detection Report** (`.pdf`)  
  Detailed report including email samples, risk classification, and prevention guidelines.  

- **Sample Email Headers and Analysis** (`.txt`)  
  Email header evidence and analysis for each.  


---

## Tools Used

- **MXToolbox** – Email header analysis & relay tracing  
- **SPF / DKIM / DMARC Validation Tools** – Authentication verification  
- **VirusTotal** – URL and link scanning  
- **PhishTank** – Phishing URL verification  
- **URLVoid** – Domain/IP reputation check  
- **Manual Header Analysis** – Checking `Received`, `Return-Path`, `Reply-To`, and origin IP

---

## Analysis Approach

1. Extract email headers from sample emails  
2. Trace sender IP and check domain reputation  
3. Verify SPF, DKIM, and DMARC authentication records  
4. Compare displayed sender address with actual origin  
5. Analyze embedded URLs and links for phishing indicators  
6. Classify risk as **Safe**, **Suspicious**, or **Phishing**  
7. Document prevention guidelines and best practices

---

## Key Findings

- Email authentication failures (SPF, DKIM, DMARC)  
- Domain spoofing and mismatched sender addresses  
- Use of free email services for reply-to addresses  
- Urgency and fear tactics in email content  
- Hidden tracking pixels or malicious attachments  

---

## Prevention Guidelines

### Do’s
- Report suspicious emails immediately  
- Verify requests via official channels  
- Check email headers when in doubt  
- Use tools to verify URLs and sender IP  

### Don’ts
- Click unknown links or attachments  
- Reply to suspicious emails  
- Trust display names alone  
- Share credentials via email

---

## Disclaimer

This repository is for **educational and cybersecurity awareness purposes only**. All samples are analyzed ethically and in a controlled environment.