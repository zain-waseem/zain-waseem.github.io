# Secure Document Approval System

A secure, role-based document approval system built for internal use by teams needing document signing, authorization, and audit trails.

## 🔐 Features
- Role-Based Access Control (RBAC) with Office365 OAuth login
- Admin and user dashboards with conditional access
- Automated PDF generation using LaTeX with dynamic signature injection
- Dockerized setup for easy deployment and environment isolation
- PostgreSQL-backed document storage and user tracking

## 🛠 Tech Stack
- Python, Django
- PostgreSQL
- Office365 OAuth
- LaTeX, Makefile
- Docker

## 📸 Screenshots
> *(Insert screenshots here: login page, dashboard, document signing flow)*

## 🚀 Getting Started (Docker)
```bash
git clone https://github.com/zainwaseem/secure-doc-approval
cd secure-doc-approval
docker-compose up --build
