STORE INVENTORY - WEB APP (PWA)

FILES
  index.html            the app
  manifest.webmanifest  makes it installable on phone
  sw.js                 offline support
  netlify.toml          Netlify settings
  icons/                app icons

DEPLOY (Netlify)
  1. Go to app.netlify.com > Add new site > Deploy manually.
  2. Drag this whole folder in. Done - open the link.

INSTALL ON PHONE
  Android Chrome: menu > Install app / Add to Home screen.
  iPhone Safari: Share > Add to Home Screen.

SETTINGS
  Open index.html and edit USER_ID, PASSWORD and API_URL at the top of the script.
  After changing any file, re-upload the folder. If the phone still shows the old
  version, close and reopen the app (or raise CACHE version in sw.js: v1 -> v2).

NOTE
  The User ID/Password are checked inside the page, so anyone who views the page
  source can read them. Fine for casual use, not real security.
