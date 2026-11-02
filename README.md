# claims-api

Golden-path reference service. Push to `main` → GitHub Actions builds the image, pushes it to ACR and bumps the SIT tag in `platform-gitops` → Argo CD deploys. Open a PR → you get a preview environment.
