# Infra / deployment notes

MVP recommended stack:
- Backend: Containerized NestJS -> GCP Cloud Run (or AWS Cloud Run equivalent)
- Database: Cloud SQL (Postgres)
- Auth: Firebase Auth (phone + email)
- Storage: Cloud Storage / S3
- Queue: Redis (managed)

Terraform templates and sample manifests can be added in infra/ when you decide on provider. For a fast MVP use Cloud Run + Cloud SQL.
