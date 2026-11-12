Hi, I'm Võ Quốc Khánh 👋

Information Assurance student at FPT University (K20, 2024–2028). I'm interested in malware analysis, web application security and applying machine learning to security problems. Currently looking for an OJT internship in Đà Nẵng (Spring 2027).

🔬 Projects
UNMASK – Repacked or Novel?

IAM302 · Fall 2026 · Team lead (4 members)

A filter that tells apart known malware that was only repacked from genuinely new malware, so drift detectors raise fewer false alarms.

Built a dataset of 596 Windows PE files from 9 malware families (AgentTesla as the core), packed with UPX and MPRESS, split by original sample to avoid leakage.
Reduced the false-trigger rate from 15.8% to 8.2% on a 404-sample test set; the difference is statistically significant (McNemar, p < 0.001).
My part: sample collection, packing, building and freezing the dataset, reviewing results, writing the report.

Python scikit-learn PE static analysis UPX MPRESS

AIC211 – Phishing & BEC Email Detection

AIC211 · Summer 2026 · Team member (4 members)

Classifies emails as benign, phishing or Business Email Compromise (BEC) — fake “boss” emails that ask for money and usually contain no malicious link or file.

Trained Naive Bayes, Linear SVM and XGBoost on 63,305 emails from a public dataset.
The selected model (Linear SVM) catches over 99% of malicious emails on a 9,496-email test set and misses only 1 of 622 BEC emails.
8-step pipeline from data cleaning to a demo that predicts new emails and explains the signals behind each prediction; fixed a TF-IDF data-leakage issue.

Python scikit-learn XGBoost TF-IDF NLTK

GEs – Travel Social Network

PWD301 · Fall 2026 · Team lead (5 members) · Live at ges.id.vn

A social network for sharing trips, planning itineraries, chatting and getting place suggestions by free time, transport and budget.

Suggests 9,072 places in Ho Chi Minh City from OpenStreetMap; place search covers all 34 provinces.
Deployed with Docker behind Cloudflare Tunnel.
My part: backend/frontend, admin panel and role-based access control (RBAC); reproduced and fixed Broken Access Control (OWASP A01). The team also added protection against SQL Injection, XSS and brute-force (rate limiting).

Flask SQLAlchemy pytest Docker OWASP Top 10

IT Risk Management for Universities

IAA202 · Fall 2026 · Team lead (4 members) · report only, no code

Identified 54 IT risks in 9 groups and scored them with NIST SP 800-30 / ISO 31000 (12 high, 37 medium, 5 low).
The team proposed 16 controls, a 3-phase roadmap, a 72-hour ransomware response playbook for exam week, and a cost–benefit analysis.
My part: risk identification, analysis, evaluation and the conclusion.
🛠️ Skills
Security: OWASP Top 10, RBAC, static malware analysis (PE), risk management (NIST / ISO)
Programming & ML: Python, Flask, SQLAlchemy, scikit-learn, XGBoost
Tools: Linux (Kali, Ubuntu), Docker, Git, Wireshark, Nmap
🤝 Beyond code

Led “Học Cùng Em 2”, a charity project that raised 5,698,686 VND and gave 175 gift packages to orphaned children at a temple shelter in Ho Chi Minh City, with fully public income and expense statements.

📫 quockhanhtkh2.com@gmail.com
