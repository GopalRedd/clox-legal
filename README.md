# Clox legal website

Static GitHub Pages website for Clox, containing the landing page, Privacy Policy and Terms & Conditions.

## Before publishing

1. Replace `[REPLACE WITH DEVELOPER / PUBLISHER NAME]` in `privacy-policy.html` and `terms-and-conditions.html` with the publisher's legal name.
2. Replace `[REPLACE WITH SUPPORT EMAIL]` in both policy pages with the support email address.
3. Replace `REPLACE_WITH_SUPPORT_EMAIL` in `index.html` with the same email address.
4. Review the policy text against the final app build, SDKs, Android permissions and actual data practices.

## Publish with GitHub Pages

1. Create a **public** GitHub repository named `clox-legal` (keep the Flutter app repository separate and private).
2. Upload all files in this folder to the root of the repository.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then Save.
6. Wait for the Pages deployment to finish. Your site will be at `https://YOUR-GITHUB-USERNAME.github.io/clox-legal/`.

Policy URLs:
- `https://YOUR-GITHUB-USERNAME.github.io/clox-legal/privacy-policy.html`
- `https://YOUR-GITHUB-USERNAME.github.io/clox-legal/terms-and-conditions.html`

GitHub Pages on GitHub Free requires a public repository. The legal pages are public by design; do not put app source code, secrets, signing keys or private information in this repository.
