PACKPAUSE — Final Website
=========================

A minimal, English-language, mobile-first smoking habit recording and support prototype.

WHAT'S INCLUDED
- index.html: entire website; no build step or external libraries
- apple-touch-icon.png: iPhone Home Screen icon
- favicon.png: browser icon
- icon-192.png: additional app icon

PUBLISHING TO GITHUB PAGES
1. Create a GitHub repository (for example, "packpause").
2. Upload all four website files to the repository root, not a nested folder.
3. In Settings > Pages, select Deploy from a branch, then select your main branch and / (root).
4. Once published, open https://YOUR-USERNAME.github.io/packpause/ (replace the placeholders).
5. Write that exact URL to your NFC sticker. Use the same URL for Safari > Share > Add to Home Screen.
6. Both entry methods begin on the Pause screen. The Today tab contains recordings and the 14-day history.

USE AND LIMITATIONS
- The NFC sticker stores only the website URL. An NFC-compatible unlocked phone is needed to open it; reading behavior varies by device.
- Records are saved in the browser on the current device. Safari and an iPhone Home Screen web app may use separate website-data storage, so syncing between these two entry methods is NOT guaranteed.
- Demo mode (Settings > Try demo) uses clearly labeled sample data and does not overwrite real records.
- You can correct an accidental tap with Undo, or adjust saved totals using Today > Edit totals.
- Export your records from Settings before clearing browser data or switching devices.
- This is a student prototype, not medical treatment or a substitute for professional stop-smoking support.

FINAL REVIEW
- Tested with an offline Chromium browser harness at 320, 375, 390, 428, and 768 CSS-pixel widths.
- Checked: Pause entry, three intervention paths, timer, recording, Undo, totals editing, 14-day chart,
  demo separation, data persistence, and reading older V17 local data.
- No page-script errors or horizontal overflow in those tests.
- Real NFC hardware and iPhone Safari have not been tested here and should be verified after deployment.
