# 🚀 AI-Powered Legal Document Analyzer  
An end-to-end NLP-driven system that automatically summarizes legal documents, extracts key clauses, and identifies potential risks using transformer-based models and Gemini API. Designed with a clean and modern web interface built using **React + TypeScript + Vite**.

---

## 📌 Project Overview

Legal documents are long, complex, and time-consuming to review. This system simplifies the process by allowing users to upload a document and instantly receive:

- ✔ A concise summary  
- ✔ Extracted legal clauses  
- ✔ Risk analysis & red-flag detection  
- ✔ Structured insights through a web-based UI  

The project integrates **Gemini AI**, **PDF parsing**, and a modular **TypeScript architecture**.

---

## 🎯 Features

### 🔹 Document Summarization  
- Generates high-quality abstractive summaries.  
- Reduces long legal text into short meaningful sections.

### 🔹 Clause Extraction  
Automatically identifies important clauses like:  
- Governing Law  
- Confidentiality  
- Indemnity  
- Termination  
- Payment Terms  
- Liability & Limitations  

### 🔹 Risk Identification  
- Flags suspicious or harmful clauses.  
- Detects ambiguity, hidden risks, and compliance issues.

### 🔹 Modern Web Application  
- Built using React + TypeScript  
- Clean UI for uploading files and viewing results  
- Fast Vite dev server  
- API-first architecture using Gemini AI  

---

## 📂 Project Structure (Updated Based on Repository)

```

📦 AI-Powered-Legal-Document-Analyzer
├── Documentation/
│   ├── legal_doc_analyzer_guide.md
│   └── additional_notes.md
│
├── components/
│   ├── FileUploader.tsx
│   ├── OutputBox.tsx
│   └── Loader.tsx
│
├── services/
│   ├── geminiService.ts
│   └── pdfParser.ts
│
├── App.tsx
├── index.tsx
├── index.html
├── constants.ts
├── types.ts
├── metadata.json
├── package.json
├── package-lock.json
├── tsconfig.json
├── vite.config.ts
└── README.md

````

---

## 🧠 Tech Stack

### **Frontend**
- React  
- TypeScript  
- Vite  
- Tailwind / Custom CSS  

### **AI Backend**
- Google Gemini API  
- Custom NER rule-based extraction  
- PDF text extraction  

### **Utilities**
- pdf.js / pdf-parser  
- Node.js  
- Environment variables (.env.local)

---

## ⚙️ How It Works

### 1️⃣ Input  
User uploads a PDF or pastes text.

### 2️⃣ Processing  
Text is parsed → cleaned → sent to Gemini API.

### 3️⃣ AI Analysis  
Gemini returns:  
- Summary  
- Key clauses  
- Risk score & explanation  

### 4️⃣ Output UI  
Results displayed in a clean, structured layout.

---

## ▶️ Run Locally

### **Prerequisites**
- Node.js  
- Gemini API Key  

---

### **1. Install Dependencies**
```bash
npm install
````

### **2. Configure API Key**

Create a file named:

```
.env.local
```

Add:

```
GEMINI_API_KEY=your_api_key_here
```

### **3. Run Development Server**

```bash
npm run dev
```

App will start at:
👉 [http://localhost:5173](http://localhost:5173)

---

## 🌐 Deployment

This app can be deployed on:

* Vercel
* Netlify
* GitHub Pages
* Render
* Cloudflare Pages

Add `GEMINI_API_KEY` to deployment environment variables.

---

## 📘 Documentation

All documentation is inside the **Documentation** folder:

* System architecture
* Prompt engineering guide
* Developer notes
* Workflow explanation

---

## 🧪 Future Enhancements

* OCR support for scanned images
* Multilingual document analysis
* Fine-tuned Legal-LLM integration
* Automated contract comparison
* Downloadable analysis report (PDF)

---

## 🤝 Contributing

Contributions and suggestions are welcomed.

---

## 🏅 Certification

This is to certify that the project entitled **“AI-Powered Legal Document Analyzer”** submitted by **PRATIPAL KUMAR SINGH (Roll No. 1323607)** as *Development and Implementation Support*, and **SANJU KUMARI (Roll No. 1323544)** & **Jitendra Kumar (Roll No. 1323612)** for *Ideation, Execution, and Overall Handling*, students of **BCA 3rd Year, Bachelor of Computer Application**,  
**M. M. Institute of Computer Technology & Business Management (MCA Department)**,  
**Maharishi Markandeshwar (Deemed to be University), Mullana–Ambala**,  
is a bona fide record of work carried out by them with institutional and industrial guidance.

We hereby certify that the content of this project is original and has **not been submitted** to any other university or institute for the award of any degree or diploma.

**Date:** 15/08/2025 – 16/11/2025  
**Place:** Ambala, Haryana  

---

## 🙏 Acknowledgements

We express our heartfelt gratitude to everyone who contributed to the successful completion of this project:

- **M. M. Institute of Computer Technology & Business Management (MMICT&BM)** for academic and infrastructural support  
- **Faculty mentors and supervisors** for their encouragement, guidance, and expert insights  
- **Google Gemini API, React, TypeScript, and the open-source developer community** whose tools and research enabled the technical success of this project  
- **Industry professionals and institutional support teams** for providing direction, validation, and real-world perspective  
- **Family, friends, and peers** for their constant motivation, feedback, and support  

Their collective contributions made this AI-powered system a valuable and practical implementation for legal text analysis.

---

## 📜 License (MIT License)

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
