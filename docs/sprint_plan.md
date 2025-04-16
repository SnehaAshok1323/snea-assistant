
# 🗓️ Sprint Plan: SNEA Assistant (MVP Development)

### 📋 Overview
This sprint plan outlines the 7-day agile-based development schedule for the SNEA (Simple Network Engine Assistant) project. Each sprint delivers a self-contained, testable module contributing to the final MVP chatbot.

---

## ✅ Sprint Schedule

### 🚀 **Day 1: Intent Setup + UI Skeleton**
- Create Dialogflow agent (SNEA)
- Define base intents: Welcome, Help, Balance Inquiry
- Create HTML/CSS chatbot UI template
- Set up basic input/output and quick reply layout
- Push all to GitHub

### 🔄 **Day 2: Static Responses + Simulated Data**
- Populate intents with static responses
- Define simulated account/loan/card data
- Implement response rendering in frontend
- Store mock user data in Firestore
- Test conversation flows

### 🤖 **Day 3: n8n Workflow Automation**
- Set up local n8n instance
- Create webhook workflow for triggered intent (e.g., alert or lead creation)
- Connect Firebase with n8n via HTTP endpoints
- Simulate data flow and automation

### 🔐 **Day 4: User Auth + Session**
- Enable Firebase Authentication (email/password)
- Protect Firestore with security rules
- Show different UI states (logged in vs anonymous)
- Track user session and attach conversation

### 🧪 **Day 5: Testing & Fixes**
- Manual testing of all intents and UI elements
- Fix flow interruptions or fallback errors
- Test data writes (Firestore) and webhook responses
- Perform test coverage report (manually or via notes)

### 📊 **Day 6: Docs & Analytics**
- Enable Firebase Analytics for intent logging
- Add custom events (chat start, intent trigger)
- Write internal technical documentation
- Update `README.md` with setup instructions

### 🚢 **Day 7: Final QA & Deployment**
- Final code cleanup
- Deploy to Firebase Hosting
- Share live chatbot URL
- Perform final UAT with test queries
- Freeze MVP and prepare retrospective

---

## 📌 Notes
- Each sprint should end with a commit + push
- Daily checkpoints will guide feature stability
- Documentation is written alongside code (no backlogging)

---

**Created by:** Sneha AJITHKUMAR  
**Date:** April 2025
