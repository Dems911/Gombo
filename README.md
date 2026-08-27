# Gombo

Gombo — plateforme de mise en relation de services à la demande (mobile iOS/Android, admin, backend, infra).

Scaffold initial (MVP-ready): mobile Flutter app, backend NestJS + Prisma, admin React, infra examples, CI/CD workflows.

Repository structure
- mobile/ — Flutter app (iOS/Android/web) skeleton with i18n
- backend/ — NestJS API skeleton + Prisma schema + seed script
- admin/ — React admin skeleton (MUI/Tailwind)
- infra/ — Terraform / deployment notes
- .github/workflows/ — build/test/deploy workflows
- docs/ — architecture, PSP comparatif initial, backlog

Next steps (immediately)
1. Add repository secrets (Settings → Secrets) — see docs/SECRETS.md for keys.
2. Provide Firebase config files (google-services.json, GoogleService-Info.plist) in CI secrets or local dev.
3. Run local dev:
   - Backend: cd backend && yarn install && yarn dev
   - Mobile: cd mobile && flutter pub get && flutter run
   - Admin: cd admin && yarn install && yarn start

See docs/ for deployment and PSP comparatif.
