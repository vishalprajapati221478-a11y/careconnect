# CareConnect — Community Healthcare Access Demo

A responsive five-page static website made with HTML, CSS and vanilla JavaScript.

## Files
- `index.html` — Home
- `services.html` — Search healthcare service categories and try a demo appointment request with confirmation popup
- `how-to-use.html` — Online consultation guide
- `awareness.html` — General health awareness articles
- `contact.html` — Demo contact form and emergency information
- `styles.css` — Shared responsive design
- `script.js` — English/Hindi/Marathi translations, search, mobile navigation, demo form behavior

## Run locally
1. Extract `CareConnect.zip`.
2. Open `index.html` in a modern browser. The pages work as static files.
3. For a local development server, open a terminal in the folder and run:
   - Python: `python -m http.server 8000`
   - Then visit `http://localhost:8000`
4. Use the language menu in the header to switch between English, Hindi and Marathi.

## Publish with GitHub Pages
1. Sign in to GitHub and create a new public repository, for example `careconnect`.
2. Upload all six website files (`index.html`, `services.html`, `how-to-use.html`, `awareness.html`, `contact.html`, `styles.css`, `script.js`) and this README.
3. Open repository **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for deployment and open the URL shown in the Pages settings. It usually resembles `https://YOUR-USERNAME.github.io/careconnect/`.

## Important limitations
- This is an educational front-end demo, not a medical service.
- Service cards are illustrative categories, not verified doctors or providers.
- The appointment form is a demo only: it shows a confirmation popup but does not book a real appointment; no video call, chat, or doctor directory is connected.
- The contact form only displays a local confirmation and does not send or store submissions.
- Do not enter real medical records or other sensitive information.
- Emergency information: India emergency number 112. For an emergency, contact local emergency services directly.
- Health information is general education and is not a substitute for professional advice or emergency care.

## Suggested upgrades
- Connect an actual appointment API and backend only after setting up authentication, privacy, security, and appropriate compliance.
- For feedback collection, create a Google Form separately and link it from the site.
