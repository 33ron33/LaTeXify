# LaTeXify

This Repository will be used to create an **Application** (Mobile-first: iOS & Android) and later a **Website Backend** where we build a platform to:

> Instantly transform handwritten notes, textbook pages, Word documents, and PDFs into clean, editable LaTeX code, making scientific writing faster, easier, and accessible to students, researchers, and academics worldwide.

---

# Vision

**LaTeXify** aims to bridge the gap between analog thinking (handwritten notes, physical documents) and digital publication (LaTeX papers, theses, reports), empowering researchers to focus on ideas instead of formatting.

"**From Snap to Publish in Seconds.**"

---

# Roadmap

## 1. Environment Setup
- Install Flutter SDK and Dart.
- Install Android Studio / VS Code with Flutter & Dart plugins.
- Set up emulators and device testing.
- Initialize Git repository for version control.

## 2. Application Development Plan

### Phase 1: Mobile App (MVP for iOS & Android)
- App Initialization and Structure
- Home Screen:
  - Capture Image (Camera/Gallery)
  - Upload Word/PDF Documents
- Real-time OCR Processing:
  - Basic Tesseract/MLKit OCR integration
  - Mathpix API integration (for premium high-accuracy conversion)
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

### Phase 2: Backend Development
- Custom Python (FastAPI) backend:
  - Handle DOCX to LaTeX conversion (Pandoc)
  - Handle PDF to LaTeX conversion (PyMuPDF + OCR)
  - Secure API endpoints (Authentication tokens)
- Deploy backend using Cloud Run or AWS Lightsail
- (Later) Host Landing Page Website

### Phase 3: Advanced Features (Post-MVP)
- Real-time LaTeX Preview (MathJax/Katex rendering)
- Collaborative Features (Share with peers)
- Project Management (Group images/docs into LaTeX Projects)
- Equation Editor Toolbar (Insert symbols easily)
- Direct Overleaf Integration (Stretch Goal)
- Offline OCR Mode (limited)


---

# Timeline

| Week | Milestone |
|:---|:---|
| Week 1 (Apr 29) | Environment Setup, Wireframes, Project Creation |
| Week 2-3 (May 6) | Core App Screens (Image Picker, Doc Picker, OCR Integration) |
| Week 4-5 (May 20) | Backend Setup (DOCX/PDF API), Integrate with App |
| Week 6 (May 27) | Finalize OCR Logic, Editing Screen, Export Features |
| Week 7 (June 3) | Firebase Auth, Usage Tracking, Analytics Setup |
| Week 8 (June 10) | Monetization Integration, Beta Testing (TestFlight, Play Store Internal) |
| Week 9 (June 17) | App Store Submission, Google Play Submission |
| Week 10 (June 24) | Launch Publicly |

---

# Tech Stack

- **Frontend (Mobile App):** Flutter, Dart
- **Backend:** Python (FastAPI), Pandoc, OCR Engines (Tesseract, Mathpix API)
- **Authentication:** Firebase Authentication
- **Database:** Firestore
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
  - Higher priority OCR (e.g., Mathpix integration)

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
