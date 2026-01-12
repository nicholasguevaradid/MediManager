# MediManager
Este proyecto es para aprender a usar diferentes tecnologias y tambien para ayudar a casas para adultos mayores
# MediManager (Demo/Educational EHR) — Week 1

> Educational/Demo only. No real patient data. No diagnosis logic.

## Services (Week 1)
- auth-service (.NET 8): register/login, JWT, RBAC (Admin/Doctor/Nurse)
- ehr-service (.NET 8): Patients + MedicalRecords CRUD (protected by JWT+RBAC)
- sqlserver (container) + db-init (creates databases)

## Prereqs
- Docker + Docker Compose
- (Optional) .NET 8 SDK if you want to run services outside containers

## Configure secrets
Copy `.env.example` to `.env` and change passwords/secrets.

## Run locally
```bash
docker compose up --build
