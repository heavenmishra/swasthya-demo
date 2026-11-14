# Swasthya — Sambalpur healthcare booking demo

A responsive, static front-end demo for a local healthcare discovery and appointment-request platform. Built with plain HTML, CSS and JavaScript so it can be hosted directly on GitHub Pages.

## Run locally

1. Download or clone this folder.
2. Open `index.html` in a modern browser. No build step or package installation is required.
3. For a local web server (optional), run `python -m http.server 8000` from this folder and open `http://localhost:8000`.

## Publish on GitHub Pages

1. Create a new GitHub repository (for example, `swasthya-sambalpur-demo`).
2. Upload **all four files** (`index.html`, `styles.css`, `app.js`, `README.md`) to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for the Pages deployment to finish. Your public demo URL will look like `https://YOUR-USERNAME.github.io/swasthya-sambalpur-demo/`.

## Demo interactions

- Search sample providers by name, speciality, clinic or area.
- Filter by speciality and sort by indicative consultation fee.
- Open a clinic information panel.
- Submit a sample appointment request and see a demo confirmation.
- Try the diagnostic enquiry, patient login and provider partnership forms.
- Responsive navigation and layouts adapt for mobile, tablet and desktop screens.

## Important demo limitations

- All provider names, credentials, clinic details, availability and fees are **illustrative sample data**, not verified real-world listings.
- Forms run only in the browser. They do not send, store or transmit patient information, and appointment requests do not reach a clinic.
- There is no authentication, database, payment processing, SMS/WhatsApp reminder, provider dashboard, admin dashboard or medical-record handling in this static demo.
- Do not enter real patient or health information. Before production use, implement secure backend services, consent and privacy notices, access controls, audit logs, verified provider onboarding, reliable availability sync and applicable legal/regulatory review.

## Project structure

```text
swasthya-sambalpur/
├── index.html
├── styles.css
├── app.js
└── README.md
```
