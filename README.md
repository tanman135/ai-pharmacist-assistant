# AI-Powered Pharmacist Assistant

## Overview
Pharmacists often struggle with **illegible handwritten prescriptions**, leading to **medication errors** and inefficient workflows. This **AI-powered Pharmacist Assistant** automates **prescription reading, verifies medicines, and generates structured digital orders**.  
Using **Optical Character Recognition (OCR) and Natural Language Processing (NLP)**, the system extracts text from prescriptions, matches drugs to an inventory, and enhances accuracy, efficiency, and safety.

---

## Features
✅ **Prescription Handwriting Recognition** – Extracts text using OCR  
✅ **Medicine Name Identification** – Detects drug names and dosages using NLP  
✅ **Order Generation** – Matches medicines with pharmacy inventory and creates orders  
✅ **Error Reduction** – Minimizes misinterpretation of handwritten prescriptions  
✅ **User-Friendly Interface** – Allows pharmacists to upload prescriptions easily  

---

## Tech Stack
| **Category**  | **Technology Used** |
|--------------|----------------------|
| **Frontend** | HTML, CSS, Django Templates |
| **Backend** | Django |
| **Database** | PostgreSQL (or SQLite for development) |
| **OCR** | Tesseract OCR, OpenCV, Google Vision API |
| **NLP** | SpaCy, Rule-Based Text Processing |
| **Deployment** | (Optional) AWS, Firebase, or Railway for hosting |

---

## System Architecture
1️⃣ **Upload Prescription** – The pharmacist uploads a scanned prescription.  
2️⃣ **OCR Processing** – The system extracts handwritten text from the image.  
3️⃣ **NLP Processing** – Identifies medicines, dosages, and instructions.  
4️⃣ **Database Matching** – Compares extracted medicines with inventory.  
5️⃣ **Order Generation** – Creates a structured digital order for fulfillment.  

---

## Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/ai-pharmacist-assistant.git
cd ai-pharmacist-assistant
