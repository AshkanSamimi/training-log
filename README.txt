LIFT LOG: your training tracker as an iPhone app (offline, data stays on the phone)

ONE-TIME SETUP (about 10 minutes, easiest on a laptop)
1. Create a free account at github.com.
2. New repository: name it lift-log, set it to Public, create it.
3. In the repository: "Add file" > "Upload files". Drag in the files from this folder
   (index.html, sw.js, manifest.webmanifest, the three icon-*.png files; README is optional).
   Click "Commit changes".
4. Settings > Pages. Under "Build and deployment", Source: "Deploy from a branch",
   Branch: main, folder: / (root). Save. After a minute or two your address appears:
   https://YOUR-USERNAME.github.io/lift-log/
5. On the iPhone, open that address in Safari, tap Share, then "Add to Home Screen".
6. Open it once from the new icon while you have signal. From then on it works without signal.

GOOD TO KNOW
- Your sessions are stored only on the phone. Nothing is uploaded, and the GitHub page holds
  only the app itself (the plan, no logs).
- Always open it from the Home Screen icon: the icon and Safari keep separate data.
- Closing the app never loses data; it reloads everything when you open it again.
- After each session, tap "Save backup to Files" on the screen you see after saving.
  Each backup holds your whole history, so the newest file restores everything.
  Upload that file in the Claude chat whenever you want a progress review.
- Deleting the icon can delete its data; that is what the backups are for.
  To restore: Plan > Import backup.
- Moving over from the Claude page: there, Plan > Export backup; here, Plan > Import backup.
- Updates: upload a new index.html and sw.js to the same repository. The app picks them up
  the next time you open it with signal (close and reopen once if needed).
