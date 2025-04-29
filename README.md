# LaTeXify

This Repository will be used to create an **Application** (Mobile-first: iOS & Android) and later a **Website Backend** where we build a platform to:

> Instantly transform handwritten notes, textbook pages, Word documents, and PDFs into clean, editable LaTeX code, making scientific writing faster, easier, and accessible to students, researchers, and academics worldwide.

---

# Vision

**LaTeXify** aims to bridge the gap between analog thinking (handwritten notes, physical documents) and digital publication (LaTeX papers, theses, reports), empowering researchers to focus on ideas instead of formatting.

"**From Snap to Publish in Seconds.**"

---

# Roadmap

## Phase 1: Backend Development (April–Mid May)

> Focus: Build a robust backend with OCR and ChatGPT LaTeX conversion.

### ✅ Goals:
- Set up Python FastAPI server.
- Integrate OCR engine (Tesseract for now).
- Connect OpenAI ChatGPT API to convert raw OCR output to clean LaTeX.
- Create endpoints:
  - `/convert/image` → OCR + ChatGPT LaTeX cleanup
  - `/convert/docx` → DOCX to LaTeX using Pandoc
  - `/convert/pdf` → PDF to LaTeX via OCR or text extraction
- Return LaTeX output to be used by frontend.

### 🔍 Testing Plan for Phase 1:
- Test image-to-LaTeX on:
  - Printed textbook page
  - Handwritten math
  - Mixed text + equations
- Measure backend accuracy with:
  - **Equation correctness rate > 90%**
  - **LaTeX syntax error rate < 5%**
  - **Processing time < 10s per image**
- Validate document conversion from:
  - DOCX files with math equations (Word Equation Editor)
  - PDFs (scanned + selectable text)

✅ Once accuracy thresholds are met, we move to Phase 2.

---

## Phase 2: Mobile App (MVP for iOS & Android)
- Flutter App Setup
- Home Screen:
  - Capture Image (Camera/Gallery)
  - Upload Word/PDF Documents
- Call Backend API endpoints
- Display LaTeX Output:
  - Editable TextArea for corrections
  - Export Options:
    - Save as .tex file
    - Share via system share sheet
    - Copy to Clipboard
- Authentication:
  - Firebase Auth (email/password, Google Sign-in)
- Usage Tracking:
  - Free Tier Limits (5 conversions/day)
- In-app Purchases:
  - Monthly/Yearly Subscription for unlimited conversions
- Analytics and Crash Reporting:
  - Firebase Analytics, Crashlytics integration

---

# Tech Stack

- **Backend:** Python, FastAPI, OpenAI ChatGPT API, Tesseract, Pandoc
- **Frontend:** Flutter (Dart)
- **Authentication:** Firebase Authentication
- **Database:** Firestore (Firebase)
- **Analytics:** Firebase Analytics
- **Crash Reporting:** Firebase Crashlytics
- **Deployment:** Firebase Cloud Run / AWS Lightsail

---

# Monetization Strategy

- Free Tier: 5 conversions/day
- Subscription:
  - $4.99/month OR
  - $29.99/year
- Premium Features:
  - Unlimited conversions
  - Higher priority OCR (e.g., Mathpix or GPT-powered enhancement)

---

# Timeline

| Week | Milestone |
|:---|:---|
| Week 1 (Apr 29) | Backend Setup, FastAPI, Tesseract, ChatGPT API integration |
| Week 2–3 (May) | Test and benchmark OCR + GPT output (accuracy + speed) |
| Week 4–5 (May 20) | DOCX + PDF endpoints, finalize backend |
| Week 6 (May 27) | Start frontend Flutter integration |
| Week 7 (June 3) | Finalize frontend + backend connection |
| Week 8 (June 10) | Add monetization, test flows |
| Week 9 (June 17) | Publish to App Stores |
| Week 10 (June 24) | Launch LaTeXify 🚀 |

---

# Future Growth Plans

- Academic partnerships (libraries, universities)
- Outreach via online academic communities (Reddit, LinkedIn, ResearchGate)
- Potential Overleaf Partnership or Acquisition
- Open Source Certain Components (optional)

---

# Project Values

- Speed: Deliver LaTeX output in seconds.
- Accuracy: Highest OCR precision for scientific and mathematical content.
- Accessibility: Affordable for students.
- Privacy: User data handled with highest confidentiality.

---

# Let's Build LaTeXify 🚀
"Turn Ideas on Paper into Publications, Instantly."

---

(Stay tuned. Night after night, sprint after sprint.)
