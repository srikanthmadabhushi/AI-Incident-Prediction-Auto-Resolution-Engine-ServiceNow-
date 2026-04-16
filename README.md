# AI-Incident-Prediction-Auto-Resolution-Engine-ServiceNow-
## 📌 Overview
This project demonstrates an AI-inspired Incident Management system built on ServiceNow that predicts incident risk, suggests resolutions, and recommends assignment groups in real time.

---

## 💡 Problem Statement

In traditional ITSM:
- Incidents are handled reactively  
- No prediction of severity or escalation  
- Manual assignment delays resolution  

👉 Result: Increased downtime and slower incident resolution  

---

## 🎯 Solution

This project introduces an intelligent engine that:

- Calculates **Risk Score** for incidents  
- Predicts incident severity  
- Suggests resolution steps  
- Recommends assignment groups  
- Provides real-time AI suggestions via UI  

---

## 🔥 Key Features

### ✅ 1. Risk Scoring Engine
- Evaluates:
  - Priority  
  - Category  
  - Keywords (e.g., "down")  
- Generates a dynamic **Risk Score (0–100)**  

---

### 🔮 2. Incident Prediction
- Classifies incidents:
  - High Risk  
  - Medium Risk  
  - Low Risk  

---

### 🛠️ 3. Suggested Resolution
- Provides automated troubleshooting suggestions  
- Includes fallback logic for unknown scenarios  

---

### 👥 4. Assignment Recommendation
- Suggests appropriate support teams:
  - Network Team  
  - Application Support  
  - Service Desk  

---

### 🖱️ 5. Real-Time AI Suggestion Button

Custom UI Action:

Get AI Suggestion

Displays:
Prediction: High Risk Incident
Resolution: Check network connectivity and restart router
Assignment: Network Team


---

## 🏗️ Architecture

Incident Record
↓
Business Rule (AI Logic Engine)
↓
Risk Score + Prediction + Suggestions
↓
UI Action (Button)
↓
GlideAjax
↓
Script Include (IncidentAIAjax)

---

## 🛠️ Technologies Used

- ServiceNow ITSM
- GlideRecord
- Business Rules
- Script Includes
- GlideAjax
- UI Actions
- JavaScript

---

## 📸 Screenshots

### 1. Risk Score & Prediction
![Risk](screenshots/risk_score.png)

### 2. Suggested Resolution
![Resolution](screenshots/resolution.png)

### 3. Assignment Suggestion
![Assignment](screenshots/assignment.png)

### 4. UI Button
![Button](screenshots/ui_button.png)

### 5. AI Suggestion Popup
![Popup](screenshots/popup.png)

---

## 🚀 Business Value

- Faster incident resolution  
- Reduced manual effort  
- Improved decision-making  
- Proactive IT operations  

---

## 🔮 Future Enhancements

- Machine Learning-based prediction  
- Integration with AIOps  
- Automated incident resolution  
- Performance Analytics dashboard  

---

## 👨‍💻 Author

**Srikanth Madabhushi**  
🔗 Portfolio: https://SrikanthMadabhushi.github.io  

---

## ⭐ Conclusion

This project transforms traditional incident handling into an intelligent, AI-driven system that improves efficiency and operational reliability.
