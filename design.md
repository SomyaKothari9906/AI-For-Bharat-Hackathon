# System Design

## 1. Architecture
User -> Web Application -> Backend Server -> ML Model -> Database

## 2. Components
- Frontend: React / HTML-CSS
- Backend: Python (Flask/FastAPI)
- Database: MySQL / PostgreSQL
- ML Model: Classification model (Random Forest / XGBoost)

## 3. Workflow
1. Admin uploads dataset
2. Data preprocessing
3. Model detects anomalies & duplicates
4. Fraud score generated
5. Flagged records shown on dashboard

## 4. Future Enhancements
- Aadhaar verification API integration
- Real-time fraud detection
- SMS alert system
