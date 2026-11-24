MMTrack launcher: short link and home-screen icon
==================================================

These files make a small public page that opens MMTrack. It holds no data and no codes:
it only knows the app's address. People still sign in with Google and their access code.

1. Make a free GitHub account at github.com (e.g. username: mmtrack-sibu).
2. Create a new PUBLIC repository named exactly:  <username>.github.io
   (for mmtrack-sibu that is  mmtrack-sibu.github.io ). Tick "Add a README file".
3. In the repository: Add file > Upload files > drag in ALL the files from this folder > Commit changes.
4. Open index.html in the repository > pencil (Edit) > replace PASTE_YOUR_WEB_APP_URL_HERE with your
   Web app URL (Apps Script > Deploy > Manage deployments > copy the URL ending in /exec) > Commit changes.
5. Settings > Pages > Source: "Deploy from a branch", Branch: main, folder / (root) > Save.
   After a minute or two the page is live at  https://<username>.github.io

Share that address with staff. On each phone, open it once, add it to the home screen, tap Open MMTrack.
From then on the icon (and the short link) open MMTrack straight away.
Add ?stay to the address to see the page again, e.g. https://mmtrack-sibu.github.io/?stay

Own domain later (e.g. mmtrack.my): buy the domain, then Settings > Pages > Custom domain, and follow GitHub's DNS steps.
The same files keep working.
