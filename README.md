# 📝 AI vs Human Text Detector (Angular + OCR)

This project is an **AI-generated text detector** built with **Angular**.  
It lets you **type text** or **upload an image with text**, then uses simple text-analysis techniques to guess whether the text is more likely written by a **human** or by an **AI tool**.

---

## ✨ Features
- 📸 **Scan text from images** using [Tesseract.js](https://github.com/naptha/tesseract.js) (OCR).  
- ⌨️ **Type or paste text** directly into the app.  
- 🧠 **Analyzes writing patterns**, such as:
  - Sentence length & variation  
  - Word variety & repetition  
  - Use of common words (stopwords)  
  - Punctuation & capital letters  
  - Randomness of characters  
  - Cliché phrases  
- ✅ Gives a **verdict**:
  - **Likely AI-generated**
  - **Likely human-written**
  - **Uncertain / Mixed**

---

## 🖼️ How It Works (Simple Explanation)
1. **Upload or Type**  
   - Either type text directly or upload an image (screenshot, photo, scanned paper).  
   - If an image is uploaded, the app reads the text using OCR.  

2. **Text Analysis**  
   - The app looks at how sentences are structured, how often words repeat, and other patterns.  

3. **Verdict**  
   - Based on the analysis, the app estimates if the text is human or AI-written.  

---

## 🚀 Getting Started (For Developers)

### Prerequisites
- [Node.js](https://nodejs.org/) (v16+ recommended)  
- [Angular CLI](https://angular.io/guide/setup-local)

### Install
Clone the repo and install dependencies:

```bash
git clone https://github.com/reykista24/ai-text-detector.git](https://github.com/reykista24/ai-model.git
cd ai-mode
npm install
```

### Run the App
```bash
ng serve
```
Open your browser at:
👉 http://localhost:4200/
