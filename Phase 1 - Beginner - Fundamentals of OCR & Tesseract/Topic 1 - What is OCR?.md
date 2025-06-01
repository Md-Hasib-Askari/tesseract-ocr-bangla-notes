# 📘 Topic 1: What is OCR?

## 🔍 Definition:

**OCR (Optical Character Recognition)** is the technology that enables the conversion of different types of documents—such as scanned paper documents, PDFs, or images captured by a digital camera—into editable and searchable data.

---

## 💡 Key Concepts:

### 1. **Optical Character Recognition (OCR):**

* **Goal:** Identify text in images and convert it into machine-encoded text.
* **Input:** Image (printed, typed, or handwritten text)
* **Output:** Text in a digital format (TXT, DOC, JSON, etc.)

### 2. **How OCR Works (Simplified):**

1. **Image Preprocessing:** Clean the image by removing noise and correcting alignment.
2. **Segmentation:** Divide the image into regions (lines, words, and characters).
3. **Feature Extraction:** Analyze shapes and patterns of characters.
4. **Classification:** Match character patterns to known characters (e.g., using trained ML models).
5. **Postprocessing:** Spellcheck, correct formatting, apply language rules.

---

## 🧠 OCR vs. Similar Technologies:

| Term | Full Form                         | Description                                 |
| ---- | --------------------------------- | ------------------------------------------- |
| OCR  | Optical Character Recognition     | Recognizes printed/typed text from images   |
| ICR  | Intelligent Character Recognition | Recognizes **handwritten** characters       |
| OMR  | Optical Mark Recognition          | Recognizes marks like checkboxes or bubbles |

---

## 📌 Real-World Applications of OCR:

* **Document digitization**: Scanned books, newspapers, archives
* **License plate recognition**
* **Passport/ID recognition**
* **Invoice and receipt processing**
* **Automatic number plate recognition (ANPR)**
* **Translating printed foreign languages via camera (e.g., Google Translate OCR)**

---

## 🔠 OCR in Multilingual Contexts:

* OCR must support different scripts (Latin, Bengali, Arabic, etc.)
* Complex scripts like **Bengali** require specialized models due to:

  * Ligatures
  * Matras
  * Complex font styles

---

## 🔚 Summary:

OCR is the bridge between **visual information (images)** and **structured digital text**. For Bengali and other Indic languages, OCR poses unique challenges due to script complexity, which tools like **Tesseract** aim to address with specialized training.
