Dayflow PWA upgrade files

1) Upload manifest.json and service-worker.js to the root of your GitHub repository.
2) Upload the entire icons folder (with icon-192.png and icon-512.png) to the repository root.
3) Open index-html-changes.txt and add the two code snippets to your existing index.html exactly where instructed.
4) Commit the changes to the main branch.
5) Wait for GitHub Pages to deploy, then open https://mdshipon97.github.io/daily-planner/ in Chrome and refresh.

Notes:
- This enables installability and a basic offline app shell.
- Existing planner data remains in browser Local Storage. This does not add cloud sync.
- After changing app files in future, update CACHE_NAME in service-worker.js (for example v1 to v2) so installed users receive the latest cached assets.
