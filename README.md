# FinovaultX – Secure Money Movement with a Verifiable Ledger

**FinovaultX** is a secure financial transaction management system designed to ensure that money transfers are accurate, traceable, and protected against duplicate requests and concurrent transaction errors.

## 🎯 Problem Statement

Financial systems must guarantee that money is never accidentally created, lost, or transferred twice.

FinovaultX aims to solve these challenges using double-entry bookkeeping, database transaction management, idempotency, concurrency control, and role-based access control.

## 🚀 Planned Features

- User authentication and role-based access control.
- Account creation and management.
- Deposit and withdrawal operations.
- Account-to-account money transfers.
- Double-entry bookkeeping.
- Idempotency to prevent duplicate transactions.
- Concurrency control to prevent overdrafts.
- Immutable transaction ledger.
- Transaction history and audit trail.
- Auditor dashboard with read-only access.
- Automated financial integrity and security tests.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Frontend | React |
| Styling | Tailwind CSS |
| Backend | Java + Spring Boot |
| Database | PostgreSQL |
| Security | Spring Security |
| Authentication | JWT |
| Database Access | Spring Data JPA |
| Testing | JUnit 5, Mockito |
| Version Control | Git and GitHub |

## 🏗️ Architecture

```text
                React Frontend
                      |
                      v
              Spring Boot Backend
                      |
          +-----------+-----------+
          |           |           |
          v           v           v
     Authentication  Account   Transaction
        Service      Service     Service
                                  |
                                  v
                          Double-Entry Ledger
                                  |
                                  v
                              PostgreSQL
```

## 🔐 Core Financial Integrity Principles

1. Total debits must always equal total credits.
2. Every financial transaction must be atomic.
3. The same idempotency key must never execute a transfer twice.
4. Concurrent transactions must not cause account overdrafts.
5. Completed ledger entries must not be silently modified or deleted.
6. Every financial operation must be authorised and auditable.

## 🧪 Testing Strategy

The project will include tests for:

- Money conservation.
- Duplicate transaction requests.
- Concurrent withdrawals.
- Insufficient account balance.
- Unauthorised access.
- Role-based permissions.
- Ledger integrity.
- Transaction rollback on failure.

## 📁 Project Documentation

- `THREATS.md` – Security threats and mitigation strategies.
- `PROMPTS.md` – AI-assisted development records.
- `API_DOCUMENTATION.md` – API endpoint documentation.
- `schema.sql` – Database schema and setup.

## 📌 Project Status

**Status: Under Development**

Features will be marked as completed only after implementation and successful testing.

## 👨‍💻 Developer

**Gowtham Reddy Bontu**

Snovasys Fresher Hiring Challenge 2026 – VVIT
