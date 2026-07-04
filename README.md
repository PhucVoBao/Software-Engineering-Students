# SE Career Compass

Personalized Career Orientation & Learning Roadmap Platform for Software Engineering Students

Submitted by: AnNDH2

## What This Demo Covers

This is a complete frontend prototype for the Software Engineering course project. It demonstrates the main workflows from the submitted topic:

- AI Virtual Mentor: chat interface, GPA input, transcript upload signal extraction, GitHub context.
- Dynamic Roadmap: target role selection, generated skill tree, resource links, completion tracking.
- Skill Gap Analysis: current skill selection, mapping to role requirements, visual gap report, print-to-PDF flow.
- Market Pulse: simulated daily job portal scan, keyword frequency analysis, interactive chart.
- E-Portfolio: GitHub public repository sync, README/stack summarization, shareable portfolio URL.
- Actor Workspace: student, academic counselor, and industry mentor action boards.
- Course Repo: curated learning resources with search, level filter, and bookmarks.
- System Spec: functional requirement traceability, NFRs, business rules, and logical data model.
- User Management: simulated email/password login, Google OAuth flow, and persistent local records.

## How To Run

Option 1: open `index.html` directly in a browser.

Option 2: run a local static server:

```powershell
python -m http.server 4173 --bind 127.0.0.1
```

Then open:

```text
http://127.0.0.1:4173/
```

## Demo Notes

- Data is stored in browser `localStorage`, so progress stays after refresh.
- GitHub sync uses the public GitHub API when internet is available. If it fails, the app restores sample portfolio projects.
- Authentication, LLM responses, job scraping, and README AI summaries are simulated in the frontend. These are marked as prototype items in the System Spec page and can be replaced by real backend APIs later.

## Recommended Demo Flow

1. Choose a target role from the top bar.
2. Open Roadmap and mark a few nodes completed.
3. Open Skill Gap and select/unselect current skills.
4. Ask AI Mentor for internship or portfolio advice.
5. Open Market Pulse and run the daily scan.
6. Open E-Portfolio and sync a GitHub username.
7. Open Workspace to show student/counselor/mentor operations.
8. Open System Spec to explain how the demo maps to the functional requirements.
# Software-Engineering-Students
