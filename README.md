# Little Nap Planner v5 — update only

Replace only `index.html` and `sw.js` in the root of your existing GitHub Pages repository. Commit to `main`. Do not replace `icons/` or `manifest.webmanifest`.

## Changes
- Exact bedtime goal remains first priority when a valid schedule exists.
- Otherwise, early and late bedtime options appear as compact side-by-side selector buttons, including on small phones.
- Only the selected option's naps, timeline, and schedule details appear. The timeline has three colored bedtime markers on the same scale.
- Removed redundant bedtime explanation and nap-length-adjustment notices for changes within the allowed flexibility. Genuine errors and infeasible-schedule notices remain.
- Upgraded the service-worker cache to v5.

After GitHub Pages deploys, open the hosted site online once on each device and relaunch the installed app to receive the update. Saved settings remain local.
