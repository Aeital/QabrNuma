# QabrNuma — Fatima
### Death Cases & Burial Records
---

## Responsibilities

| Area | Files |
|------|-------|
| Death Cases | `deathCaseController.js`, `routes/deathCases.js` |
| Burial Records | `burialRecordController.js`, `routes/burialRecords.js` |

**Case Status Flow:** `pending` → `under_review` → `approved` → `allocated` → `completed`

---

## Frontend Pages

| Route | Description |
|-------|-------------|
| `/death-cases` | List, create, and view death cases |
| `/death-cases/[id]` | Case details & status history |
| `/burial-records` | List and create burial records |
| `/burial-records/[id]` | Burial record details |

---

## Database Tables
`death_cases` · `burial_records` · `case_status_history`

---

## Setup
```bash
# Backend
cd backend && npm install && npm run dev

# Frontend
cd frontend && npm install && npm run dev
```

*QabrNuma — Cemetery Management System*
