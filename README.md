# DNYAN AI — Phase 1 (v0.1.0)

Premium dark PWA foundation for Android and Windows.

## Included
- Responsive dashboard
- Overview, Assistant demo, Tasks, Projects, Settings
- Tasks/settings saved in browser localStorage
- PWA manifest and service worker
- No API key and no paid service required for Phase 1

## Important
The Assistant is a local demo, not connected to ChatGPT yet. Do not enter passwords, API keys, or sensitive information. Browser local data may be lost if site data is cleared.

## Run locally
A PWA service worker requires HTTPS or localhost. For a quick preview, open `index.html` in a browser (the dashboard and local demo work, but install/offline support may not).

For full PWA behavior, publish this folder to a static HTTPS host such as GitHub Pages:
1. Create a GitHub repository.
2. Upload all files and folders from this ZIP to the repository root.
3. In repository Settings → Pages, choose deploy from branch and select `main` / root.
4. Wait for the HTTPS site URL.
5. Open that URL in Chrome on Android → menu → Add to Home screen / Install app.
6. On Windows, open the same URL in Edge or Chrome → Install app.

## Basic test checklist
1. Open the site; dashboard should appear.
2. Open Tasks; add a task; reload; task should remain.
3. Mark task done; delete task.
4. Open Assistant; send a message; local demo response should appear.
5. Save a changed language in Settings; reload; setting should remain.
6. Test on a narrow mobile screen and a desktop browser.
7. After HTTPS deployment, install on Android and verify offline reopen.

## Next phase
Phase 2 adds a secure backend and official AI integration. Never put a provider API key in frontend JavaScript or a public GitHub repository.
