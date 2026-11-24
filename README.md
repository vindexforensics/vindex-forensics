# Vindex Forensics website source

A static, accessible website built from scratch with HTML, CSS, and vanilla JavaScript.

## Run locally in Ubuntu/WSL

```bash
cd ~/vindex-forensics-source
python3 -m http.server 8000 --bind 0.0.0.0
```

Open `http://localhost:8000` in the Windows browser.

## GitHub Pages

Upload the **contents** of this folder to the root of the GitHub repository. The repository root must contain `index.html`, `styles.css`, and `app.js`.

## Before production

- Replace role-based consultant cards only with verified names, photos, biographies, and credentials.
- Replace the video placeholder with a captioned MP4 and retain a text transcript.
- Connect the contact form to a reviewed secure intake service. The current form does not transmit data.
- Connect the AI guide only after privacy, retention, safety, abuse-prevention, and human-escalation controls are defined.
- Add reviewed Privacy, Terms, Accessibility, Records Retention, and Emergency pages.
- Do not display third-party logos or claim partnerships without confirmed agreements.
