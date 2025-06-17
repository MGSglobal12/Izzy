# Izzy – Integrated Case Management & Program Delivery Platform

**Izzy** is a modular and extensible ERP-style system designed to unify case management workflows across non-profit, refugee, and human services organizations. It brings operational oversight, compliance automation, and program intelligence into a single, interoperable platform.

---

## 🧩 System Overview

Izzy streamlines multi-department service delivery across:

- Legal & Immigration Case Management
- Medical Scheduling & Vaccination Tracking
- Eligibility Determination for Public Programs
- ESL Enrollment, Session Logs & Tutor Matching
- Volunteer Management with Check-In/Out
- Salesforce-based Program Evaluation & Metrics
- Structured Case Notes & Referral Workflow

---

## 🛠 Technical Architecture

| Layer       | Stack/Tooling                          |
|------------|----------------------------------------|
| Frontend   | **Knack** (Low-code UI, Role-Based UX) |
| Workflow   | **Asana** for internal sprint cycles   |
| Backend    | **Salesforce** for logic, eligibility, case routing |
| Data Sync  | Excel/Pandas-based one-time import tool |
| Automation | GitHub Actions, Python scripts         |

---

## 📦 Repository Contents

- `docs/` – Architecture, deployment, and schema
- `src/` – Knack scripts, Python ETL, Salesforce logic
- `assets/` – UI mockups and design references
- `.github/` – CI/CD, labels, issues, and milestones
- `.env.example` – Secure configuration scaffolding

---

## 🚀 Scalability & Deployment

Designed for organizations managing:
- 500+ active client records
- Multi-program compliance (ORR-5, R&P, APA)
- 7+ service departments with unique roles
- Role-based workflow automation via Knack + Salesforce

Supports containerized or no-code deployments depending on your stack maturity.

---

## 📈 Metrics & Reporting

- Referral outcome analytics
- Volunteer hour summaries
- Employment and FSSP goal tracking
- Vaccination and exemption status per region
- Interpreter usage per session

---

## 🤝 Contributor Setup

1. Clone repo and install requirements (`pip install -r requirements.txt`)
2. Copy `.env.example` to `.env` and populate secure variables
3. Follow `docs/deployment.md` to configure Knack + Salesforce apps
4. Use GitHub Actions for schema validation and script linting

---

## 📄 License

Open-source under the MIT License.
