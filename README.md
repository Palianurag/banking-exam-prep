# Banking Exam Planner

A standalone HTML banking-exam preparation planner. No build step is required.

## Run locally
Open `index.html` in a modern browser (Chrome recommended).

## Deploy with GitHub + Netlify
1. Create a new GitHub repository, e.g. `banking-exam-planner`.
2. Upload `index.html` and this `README.md` to the repository root.
3. In Netlify, choose **Add new site → Import an existing project** and connect the GitHub repository.
4. Build command: leave blank.
5. Publish directory: `.` (repository root).
6. Deploy the site.

## Important data note
This planner stores progress in the browser's `localStorage`. Data is specific to that browser/device and is not automatically synced to a database or across devices. Clearing browser data can remove saved progress, so use the planner's export/backup feature regularly if available.
