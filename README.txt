LIFT LOG: your training tracker as an iPhone app (offline, data stays on the phone)

UPDATING FROM THE PREVIOUS VERSION (you already have the GitHub page)
1. Save a backup first: in the app, Plan > Export backup (or the button after a session).
2. On github.com, open your lift-log repository > "Add file" > "Upload files".
3. Drag in ALL files from this folder (they replace the old ones with the same names). "Commit changes".
4. Wait 1-2 minutes, then open the app from the Home Screen icon with signal.
   Close it completely and open it again once; the new version loads. Your sessions stay.
   If anything looks missing: Plan > Import backup with the file from step 1.

WHAT'S NEW IN VERSION 5
- This week is planned from today on. If you edit a day that's already past this week, the preview
  and the editor say so: that change starts next week. Cardio is never stacked on a leg day.

WHAT CAME IN VERSION 4
- Changing your gym or sport days now shows a preview first ("Check before you apply": what moves
  this week and next, and which exercises are added or removed). Nothing changes until you tap
  Apply; then a green confirmation lists what changed, with Undo.

WHAT CAME IN VERSION 3
- Week tab: mark your gym days and sport days (volleyball, tennis, football). The planner picks
  4, 3 or 2 gym days and places them so no leg session lands the day before sport.
- RIR column: type how many more reps you could have done on each set. The app counts your real
  hard sets per muscle and adds load when sets were too easy.
- Sport log with RPE x minutes, a knee check, and prevention work for each sport you play.
- Cleared mode for after rehab, unlocked by the return-to-sport gates.
- "Why?" on every target opens the studies behind it, graded Strong / Moderate / Limited /
  Analogy / Practical.

ONE-TIME SETUP (only if you're starting fresh; about 10 minutes, easiest on a laptop)
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
- After each session, tap "Save backup to Files" on the screen you see after saving.
  Each backup holds your whole history, so the newest file restores everything.
  Upload that file in the Claude chat whenever you want a progress review.
- Deleting the icon can delete its data; that is what the backups are for.
  To restore: Plan > Import backup.
