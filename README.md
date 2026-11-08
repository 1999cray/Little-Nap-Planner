# Little Nap Planner — v4 nap-cycle bedtime comparison

When the requested bedtime is not feasible, the planner now prioritizes a meaningful **one-fewer-nap / one-extra-nap** comparison. The early option has a shorter nap sequence, and the late option has one additional nap. Both keep all mandatory nap start times and satisfy every wake window, including the final wake window before bedtime.

The comparison timeline shows two actual nap schedules on the **same time axis**. The **purple dashed** line is the goal, the **green** line is the earlier bedtime, and the **coral** line is the later bedtime. The earlier marker must appear before the goal; the later marker must appear after it.

If a one-nap-count difference is impossible with the constraints, the planner shows the nearest feasible alternatives and explains that limitation instead of presenting the scenarios as different nap cycles.

## Update GitHub Pages

Replace `index.html` and `sw.js` at the **repository root**, commit to `main`, and reopen the web app online once so its offline cache refreshes. `README.md` is optional. **Do not replace** the `icons/` folder or `manifest.webmanifest`; existing home-screen icons and independently saved settings are preserved.

This is a planning aid, not medical sleep guidance.
