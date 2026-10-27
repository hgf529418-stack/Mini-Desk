# Mini-Desk
Mini Desk Landscape Mode HTML
MINIDESK v1 — iPHONE DESKTOP LAUNCHER
====================================
What it does
- Landscape-friendly launcher for actual iPhone apps via Shortcuts
- Editable app icons, pinned taskbar, search, themes and saved scratchpad
- Works offline after the website is installed and cached
- Does not change iOS screen orientation or mirror to an independent TV desktop

FASTEST WAY TO GET IT ON YOUR iPHONE AS A HOME SCREEN APP
1. In Safari on your iPhone, open github.com and sign in.
2. Create a public repository called minidesk (GitHub Free Pages requires public repositories).
3. Upload all six files from this folder to the repository root:
   index.html, manifest.webmanifest, sw.js, icon-180.png, icon-192.png, icon-512.png
   (Use GitHub's Add file -> Upload files from the browser.)
4. In that repo open Settings > Pages. Under Build and deployment:
   Source: Deploy from a branch; Branch: main; Folder: /(root). Save.
5. Once GitHub gives you its Pages address, open it in SAFARI on your iPhone.
6. Safari > Share > Add to Home Screen > Open as Web App ON > Add.
7. Launch MiniDesk from your iPhone's Home Screen.

HOW TO CONNECT INSTALLED APPLICATIONS
1. In Apple Shortcuts tap + to make a shortcut.
2. Add the "Open App" action.
3. Select the real application (Microsoft Word, Xogot, Files, etc.).
4. Name the shortcut exactly "MD Word" (or "MD Xogot", "MD Files", etc.).
5. Return to MiniDesk and tap the matching tile.
6. Tap Edit apps to customize tile labels and exact shortcut names.
Note: Some side-loaded apps inside LiveContainer may not appear in the Shortcuts Open App chooser. These cannot be launched by this method unless the app exposes a usable URL scheme or is recognized by iOS as an app.

NOTES
- Word, Xogot, Files, MelonX, PlayPort default tiles require Shortcuts you create.
- Web tiles (Web, YouTube, GitHub) open links immediately.
- MiniDesk cannot read your list of installed apps or open private app files.
- AirPlay still mirrors the iPhone. To make the MiniDesk screen wide, rotate your iPhone to landscape. Other apps follow their own orientation policy.
- Data stays in the browser/Home Screen web app storage; export settings before deleting/reinstalling.
- Your repository and site will be public, so do not upload personal files, accounts or private project data.
- Only the launcher code and icons need to be published.
