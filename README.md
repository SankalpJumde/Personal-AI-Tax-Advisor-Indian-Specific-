# 🧠 Personal AI Tax Advisor [Indian-Specific] 🇮🇳
> **“Tax literacy is not just financial knowledge, but it’s financial confidence.”**

A smart **web-based AI assistant** designed to help **young professionals** understand, calculate, and optimize their income tax using **Form 16 automation, regime comparison, Section 80 tracking, and AI-driven investment suggestions.**

---

## 🚀 Problem Statement
Many young professionals in India face confusion while filing taxes:
- ❓ Which tax regime should I select?
- ❓ How much tax can I legally save?
- ❓ What are Section 80C / 80D / HRA deductions?
- ❓ How do I read Form 16 correctly?
- ❓ Which investment plans actually reduce tax?

📌 **Our Goal** – To make tax filing **simple, personalized, and intelligence-driven** using AI.  
💡 **Not replacing Chartered Accountants**, but boosting their efficiency with an AI-powered tax engine.

---

## ⚙️ How It Works
> 
```
Step I   -->  Upload Form 16 and additional user info
Step II  -->  Auto Extraction of Financial Fields
Step III -->  Review and Editable 
Step IV  -->  AI Tax Engine (FY 2025-26) Calculation
Step VI  -->  Old vs New Regime Comparison 
              + Best Regime Suggestion 
              + AI Tax Savings Suggestions
Step VII -->  Personalised Tax PDF Report
```

---

## 🔧 Tech Stack
| Component | Technology |
|-----------|------------|
| Backend | Python and Flask |
| AI Model | Python + Rule-based Tax Logic <br> + Income Tax Slabs (FY 25-26)|
| Frontend | HTML / CSS / JS |
| Form Parsing | Pdfplumber + Rule-Based Extraction |
| PDF Report | ReportLab |
| Deployment | Render |

---

## 📌 Key Features
📤 Upload **Form 16 (Govt. or Private employee)**  
✅ **Auto extraction** of financial fields  
⚖ Tax Engine based on **FY 2025–26 slab**  
🧮 **Old vs New Regime comparison**  
📲 Tracks **Section 80 deductions** (limit, used, remaining)  
📝 **Editable user inputs** anytime  
📁 One-click **AI Tax Report (PDF)**  
🤖 AI-based **investment & tax-saving suggestions**  
📈 **90%+ parsing accuracy; No OCR used**

---

## 🧠 Why It Stands Out
| Feature | Description |
|--------|-------------|
| 🧮 Real-time Regime Comparison | Calculates both regimes & suggests best |
| ✏ Editable User Data | Users can modify their details anytime |
| 📊 Section 80 Tracker | Tracks limits, usage & remaining deductions |
| ⚖ AI-Powered Decisions | Suggests smart investment plans |
| 📄 PDF Summary | Download personalised tax report instantly |

---

## 📷 Screenshots (Add Later)
> Add UI screenshots here once frontend is ready
```
📌 /screenshots  
│── home_page.png  
│── form16_upload.png  
│── tax_comparison.png  
│── pdf_report.png  
```

---

## 🗂 Project Structure

Typical repo structure:

```text
.
├─ app
   ├─ new_app.py               # Flask APP
   ├─ new_form16.py            # Form 16 Parser
   ├─ pdf_generator.py         # Personalised Pdf Report Generation
   ├─ tax_engine.py            # For Tax Calclulation 
   ├─ user_info_model.py       # Additional User Informatiom
   ├─ ai_tax_advisor.py        # if separated, else suggestion logic is in tax_calculator
├─ requirements.txt
├─ output/
   ├─ Tax_ADvisor_Report
├─ static/
│  ├─ css
|  │  ├─ style.css
│  ├─ js
|  │  ├─ script.js
│  ├─ LOGO
|  │  ├─ D:\Projects\tax-advisor-project\static\LOGO\Professional Emblem Logo for Tax Advisory.png
|  ├─ data/
|  │  ├─ chapter-VIA_Deductions.html
|  │  ├─ form-16_partA.html
|  │  ├─ form-16_partB.html
|  │  ├─ Gross_salary.html
|  |  ├─ old_new-regime.html
|  |  ├─ result_display.html
|  │  └─ TDS.html             
│  ├─ templates
|  │  ├─ index.html
|  │  ├─ review.html
|  │  ├─ result.html
|  └─ uploads/                    # runtime folder for uploaded PDFs (created on server)
|  │  ├─ sampleform16.pdf
├─ run.py

---

## 👨‍💻 Team Members
| Name | Role |
|------|------|
| **Sankalp Jumde** | AI & Backend Architecture |
| Soham Tare | Tax Engine & Logic |
| Vikrant Dhage | UI/UX & Documentation |
| Sayali Kude | Validation & Testing |

---

## 🙏 Acknowledgement
**Guided by:** *Dr. Sonia H. Bajaj*  
Your guidance helped us convert a simple idea into a practical solution. Thank you!

---

## 🛣 Future Scope
- 🧾 Multi-year tax prediction  
- 📱 Mobile app version  
- 🗣 Voice-based tax assistant  
- 🔐 Data encryption & privacy safeguards  
- 📊 CA dashboard for multiple clients  

---

## 📌 Run Locally
```bash
# Clone the repository
git clone https://github.com/your-username/personal-ai-tax-advisor.git

# Navigate to project directory
cd personal-ai-tax-advisor

# Install dependencies
pip install -r requirements.txt

# Run the backend
python run.py
```

---

## 🌐 Deployment (Coming Soon)
| Platform | Status |
|----------|--------|
| Render | ✅ Wrorking |
| AWS / Azure | 📌 Planned |
| Docker Support | ⏳ Coming Soon |

---

## 📜 License
This project is licensed under the **MIT License**.

---

## ⭐ Support & Contribution
If you like this project, please **⭐ star the repository** and share feedback!  
Contributions are welcome  fork the repo & submit a PR 🚀

---

## 📩 Contact
📧 Email: [sankalpkrishna1103@gmail.com]  
🔗 LinkedIn: [https://www.linkedin.com/in/sankalp-jumde/]  
🐙 GitHub: [https://www.linkedin.com/in/sankalp-jumde/]

---

### 🙌 Thank you for visiting!
_“Let’s make India financially smarter, one taxpayer at a time.”_ 🇮🇳
