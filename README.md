# SpeakFlow AI – privacy policy site

Static pages (no build step):

* `index.html` – English
* `vi.html` – Tiếng Việt
* `site.css` – the design (plain CSS, no external fonts or scripts, so the page contacts no third party)
* `style.css` – older style still used by `terms.html`

## Before publishing (required)

1. Contact details are filled in (Đỗ Ngọc Quý, individual developer, doquy07072002@gmail.com; no postal address). Update both pages if they change.
2. Have the text reviewed against what the released app really does. It describes the app **as of 2026-10-14**:
   local-only data, no accounts/purchases/analytics, Google AdMob + UMP, device speech recognition, AI tutor in demo mode.
   Update it (and the Play Data safety form) whenever that changes, e.g. when a real AI tutor backend, accounts,
   analytics or purchases are added.
3. This text is not legal advice.

## Publish with GitHub Pages
Repository → Settings → Pages → Deploy from branch → `main` / root. The URL will normally be
`https://doquy1.github.io/ai-learning-english-privacy/` (confirm after enabling; it returned 404 before publishing).
Use that URL in Google Play Console (App content → Privacy policy), in AdMob if asked, and as
`--dart-define=PRIVACY_POLICY_URL=<url>` in the app build so the in-app link appears.
