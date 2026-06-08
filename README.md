# 🎯 AI Privacy Janitor — Enterprise Cyber Suite

![License](https://img.shields.io/badge/License-Dual--Licensing-blue.svg)
![Security](https://img.shields.io/badge/Security-Data%20Sovereignty-red.svg)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)

**AI Privacy Janitor** is a powerful, fully independent local enterprise cybersecurity solution designed to protect organizations from corporate data leaks via public Generative AI clouds (like ChatGPT, Claude, and commercial LLMs). 

Employees love AI efficiency, but pasting sensitive text often violates compliance (GDPR, HIPAA, PCI-DSS). This suite serves as a **zero-trust local firewall** that dynamically strips, sanitizes, and replaces data with local safe masks.

---

## 📽️ Live Video Demonstration
> Check out how the system works in real-time, including the live dashboard telemetry and the background memory injection blocker!

<video src="Janitor.mp4" width="100%" controls></video>

---

## 🔥 Key Enterprise Features

* **🧠 Advanced Anti-Obfuscation Pipeline:** Defeats sophisticated adversarial input tactics (such as character-spaced text e.g., `A.l.i.c.e`, underscores, or custom delimiters).
* **🎯 Clipboard Sniper Mode:** Monitors background OS memory vectors, instantly intercepting and sanitizing sensitive text as soon as a `Copy` operation is performed.
* **📊 Compliance Audit Dashboard:** Provides security teams with live metrics on total neutralized threat vectors, categorized leaks (Names, Emails, Phone Numbers), and policy tracking.
* **📂 Bulk File Vault Scanner:** Scans entire legacy system `.txt` and `.log` files to strip out credentials before uploading or analyzing data.
* **🔒 100% Sovereign & Local Architecture:** Operates entirely within the local machine perimeter utilizing quantized offline models (`phi3`), ensuring zero external cloud transmission.

---

## 🛠️ Architecture & Flow

```text
[User Input / Clipboard] 
       │
       ▼ (Intercepted in Memory)
[Anti-Obfuscation Parsing Engine]
       │
       ▼ (PII Stripped & Redacted)
[Safe Masked Prompt Sent to AI] ───► [AI Processes Request Safely]
       │
       ▼ (Output Decoded Locally)
[Secure Final Reconstructed Output Presented to User]
💼 Commercial & Licensing Terms (Dual-Licensing)
This project is governed under a Dual-Licensing Model:

Academic & Personal Use: Free to study, test, and adapt for non-commercial educational purposes.

Enterprise & Corporate Evaluation: Any usage within corporate networks, companies, or by commercial entities requires an active operational license.

📧 Commercial Inquiries & Procurement
For corporate licensing setup, white-label deployment, or custom security rule integrations, please reach out directly via GitHub Issues or contact the lead engineer.

💳 Support & Funding the Project
Operating under highly challenging infrastructure and operational conditions in Gaza, every bit of support helps sustain development, server infrastructure integration, and further research into local privacy engineering.

If this suite added value to your enterprise infrastructure threat landscape modeling, consider supporting the development directly:

USDT (TRC-20 Address): TB1Gva3xmZg77zuGJWGTV8MM63HM1QEy3t

Developed with dedication to absolute data privacy and security sovereignty.
