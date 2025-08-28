# Pennies 
An AI-powered expense tracking app that automates logging from bills and natural text, with transparent querying and structured storage.  

---

## Problem  
Manually recording expenses is time-consuming and error-prone. For example, every day employees often note down expenses in diaries or spreadsheets and then report them — tedious and inefficient.  

---

## 💡 Solution  
**Pennies** simplifies expense tracking by combining **OCR** (bill photo to text) + **NLP** (natural text input and query).  

- Upload a photo of a bill → app extracts details (date, vendor, amount).  
- Enter natural text like *“ate lunch at KFC, paid 400 rs”* → app converts it into structured data.  
- All expenses stored in a **transparent, auditable database**.  
- Query in plain language: *“How much did I spend on food this month?”* → get results + see query process.  

Two versions:  
- **Scratch-built AI models** (for academic credit).  
- **GPT-powered version** (production-ready demo).  

---

## 🛠 Tech Stack (Planned)  
- **Frontend**: React (Web), React Native or Flutter (Mobile).  
- **Backend**: FastAPI / Node.js (for APIs).  
- **Database**: PostgreSQL (structured + reliable).  
- **AI Models**:  
  - OCR → Tesseract / PaddleOCR (custom CNN version for scratch build).  
  - NLP → spaCy / Transformers / GPT API.  
- **Deployment**: Docker + (Heroku / Render / Vercel for hosting).  

---

## 📌 Roadmap  
- [ ] Frontend design (web + mobile mockups).  
- [ ] Backend API skeleton.  
- [ ] OCR pipeline integration.  
- [ ] NLP text-to-DB parser.  
- [ ] Natural language query → DB query engine.  
- [ ] Transparent query + error handling UI.  
- [ ] Testing + polish for production-ready demo.  
