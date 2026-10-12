# tsg-cybersec-p02-muhammad-ali-kashif
Phishing Analysis and Awareness Campaign

Cyber Security Project 02 - Beginner Level

Prepared by: Muhammad Ali Kashif

Program: The Sky Gen Cyber Security Program

Date: 6 October 2026

Project Overview
This project analyzes five phishing emails obtained from public cybersecurity repositories. It examines how attackers use sender impersonation, suspicious domains, misleading links, email-authentication weaknesses and social-engineering techniques to deceive users.
The project also includes practical awareness material for non-technical employees: an A3 poster, a one-page employee guide and a ten-question quiz with an answer key.
Objectives
- Analyze five documented phishing-email samples safely.
- Compare the display name with the actual sender and reply address.
- Examine domain mismatch, lookalike domains and available domain-age evidence.
- Explain SPF, DKIM and DMARC results in plain language.
- Inspect links without opening suspicious destinations.
- Identify urgency, fear, authority, reward and scarcity tactics.
- Produce clear security-awareness material for employees.
Samples Analyzed
Sample	Phishing theme	Main indicators	Risk
1	Microsoft unusual sign-in	Sender mismatch, missing authentication and reply diversion	High
2	Binance verification	Unrelated destination, deadline pressure and failed alignment	Critical
3	Microsoft account lock	Lookalike domain and SPF, DKIM and DMARC failure	Critical
4	OneCasino promotion	URL shortener, identical action links and unrelated infrastructure	High
5	Post Fiji reward	Spoofed identity, Reply-To mismatch and advance-fee tactics	High


Repository Contents
tsg-cybersec-p02-muhammad-ali-kashif/
|- README.md
|- tsg-cybersec-p02-muhammad-ali-kashif-final-submission.pdf
|- report/
|  `- tsg-cybersec-p02-muhammad-ali-kashif-analysis-report.pdf
|- awareness-material/
|  |- tsg-cybersec-p02-muhammad-ali-kashif-awareness-poster.pdf
|  |- tsg-cybersec-p02-muhammad-ali-kashif-awareness-poster.png
|  `- tsg-cybersec-p02-muhammad-ali-kashif-employee-guide.pdf
`- quiz/
   `- tsg-cybersec-p02-muhammad-ali-kashif-awareness-quiz.pdf
Safe Analysis Method
1. The samples were reviewed as raw or documented email evidence.
2. No suspicious link or attachment was opened.
3. URLs and domains were defanged or described without making them clickable.
4. Sender, Reply-To, Return-Path and available routing information were compared.
5. Receiver-recorded SPF, DKIM and DMARC results were interpreted together with message content.
6. Verdicts were based on multiple indicators rather than one automated score.
Key Learning
Passing SPF, DKIM or DMARC does not automatically prove that an email is safe. Attackers can authenticate their own domains or misuse legitimate platforms. Employees should verify the sender, destination, request and context through an independent official channel.
Tools and References
- Public phishing samples from rf-peixoto/phishing_pot
- Public samples and analysis from jacobdcook/Phishing-Analysis-Lab
- Email-header analysis concepts from MXToolbox and Google Admin Toolbox
- VirusTotal results cited only as point-in-time reputation evidence
- MITRE ATT&CK Phishing technique T1566
- CISA phishing-awareness guidance
Safety and Ethics
This repository is for defensive education and awareness only. It does not contain raw malicious attachments, live phishing links, credentials or personal mailbox information. The official project brief is not included because it must not be published outside the program.
Author
Muhammad Ali Kashif
BS Information Technology
Cybersecurity learner focused on SOC analysis, phishing investigation and defensive security.
