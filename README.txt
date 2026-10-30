SPEAKUP AI — FIRST WORKING VERSION

What this version does:
- Runs as a mobile-friendly web app.
- English and Nepali practice prompts.
- Six role-play situations.
- Basic conversation coaching (rule-based, not generative AI yet).
- Text-to-speech and speech-to-text where the browser supports them.
- Saves practice counts locally on your device.
- Can be installed as a PWA after hosting on HTTPS.

Important:
This first version does NOT connect to an AI model. It does not send your messages anywhere. The feedback is basic coaching logic. A real AI conversation partner can be added later using an API, but free API quotas and privacy terms can change. Never put a secret API key directly in browser JavaScript.

HOW TO TEST ON ANDROID:
1. Extract the ZIP.
2. Upload the files to a static HTTPS host such as GitHub Pages.
3. Open the published HTTPS site in Chrome on Android.
4. Use Chrome menu (three dots) > Install app or Add to Home screen.
5. Open SpeakUp AI from your home screen.

GITHUB PAGES QUICK SETUP:
1. Sign in or create a GitHub account.
2. Create a new public repository named speakup-ai.
3. Upload index.html, manifest.webmanifest, sw.js, and icon.svg to the repository root.
4. Open repository Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select main and /(root), then Save.
7. Wait for the published site URL, open it on your Android phone.

Local preview:
You can open index.html in a browser to test the basic page. PWA installation and offline caching require HTTPS (or localhost).

Files:
index.html             Main app
manifest.webmanifest   Installable app metadata
sw.js                  Offline cache
icon.svg               App icon
