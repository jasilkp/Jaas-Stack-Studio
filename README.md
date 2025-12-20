# Jaas Stack Studio — Static Website

A single‑page, responsive site for Jaas Stack Studio (Muhammed Jasil KP) with About, Services, and Contact sections.

## Quick Start

Open the site by double‑clicking `index.html` or drag it into your browser.

### Optional: run a local server
If you prefer an `http://` URL for testing:

- Python 3:
  ```powershell
  # from the project folder
  python -m http.server 8080
  # then browse http://localhost:8080
  ```
- Node (npx):
  ```powershell
  npx serve . -l 8080
  ```

## Customize
- Replace the avatar: put your image at `assets/avatar.svg` (or swap the `<img>` `src` in `index.html`).
- Update brand: edit `assets/logo.svg` and `assets/favicon.svg`.
- Contact details: update WhatsApp/tel/email in `index.html` and the vCard (`assets/jaas-stack-studio.vcf`).

## Notes
- WhatsApp link uses `https://wa.me/9207431350`. If needed, update to your full international format (e.g., `https://wa.me/919207431350`).
- The contact form opens the default email client; no backend is required.
