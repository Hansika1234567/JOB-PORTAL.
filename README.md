Project: Job Portal (Recruiter + Job Seeker)

Tech: HTML, CSS, JavaScript (No Tailwind)

Data Source:
- Primary: https://jsonfakery.com/jobs
- Fallback: Local sample if API fails (CORS/offline)

Core Features:
- Add / Update / Delete jobs (Recruiter role)
- View job details in a modal
- Roles: Recruiter / Job Seeker with UI switching and saved state
- Apply to jobs (Job Seeker) with local storage submissions
- Search (title/company/location), Filter by type, Sort by date/title/salary
- Bookmarks (save/unsave) persisted locally
- Pagination with selectable page size
- Data persistence using localStorage


- Merge API results with locally created posts; dedupe by id.
- All interactions are client-side; no external navigation or backend writes.
- Defensive fallbacks and toasts for good UX.
