# Explore Agile Principles (`Agile Studio`)

An interactive, single-file HTML learning lab designed for college students with little or no prior industry experience to explore the **4 Agile Manifesto Values** and **12 Agile Principles** through campus group-project analogies, hands-on simulations, and knowledge checks.

🔗 **Live site:** [sc137.github.io/agile-principles](https://sc137.github.io/agile-principles/)

Prepared by **Professor Sable** ([cantus.us/msac](https://cantus.us/msac)) for **CISP 10** at Mt. San Antonio College (Mt. SAC) and open for anyone learning Agile fundamentals.

---

## What's Inside `index.html`

1. **Overview & Study Progress Tracker**
   - Contrasts "Finals Cram" (Waterfall) with "Iterative Lab" (Agile) workflows.
   - Tracks study milestones locally in `localStorage` and includes a plain-English **Key Terms Glossary** modal.
2. **The 4 Agile Manifesto Values**
   - Interactive balance sliders showing what breaks when a team leans too far toward zero structure, too far toward bureaucracy, or hits the Agile sweet spot.
3. **The 12 Agile Principles Explorer**
   - Filterable by theme and searchable by keyword, translating every official principle into plain college English, a campus/hackathon example, and an anti-pattern to avoid.
4. **Lab 1 — Waterfall vs. Agile Semester Trade-Off Sandbox**
   - Simulate a 6-week group project under changing requirements, check-in habits, and MVP scope discipline, with both an SVG chart and an accessible data table.
5. **Lab 2 — Hands-On Sprint & Kanban Board Simulator**
   - Move user stories across *Backlog*, *Sprint To Do*, *In Progress*, and *Done*, test WIP limits and Sustainable Pace warnings, handle mid-sprint curveballs, and run a Sprint Review.
6. **Knowledge Tests & Printable PDF Certificate**
   - **Team Scenarios (5):** Real campus project dilemmas with immediate feedback.
   - **Principle Matcher (4):** Match everyday student team habits to Agile principles.
   - **Mastery Quiz (10):** Graded quiz with per-question explanations.
   - **Claim Certificate:** Unlocks once all 5 Team Scenarios, the 4-item Principle Matcher, and the 10-question Mastery Quiz are complete. Students enter their name and save a landscape **Explore Agile Principles** PDF certificate signed by **Professor Sable**.

---

## Running Locally or Hosting on GitHub Pages

- **Zero build steps or external dependencies:** Everything lives in [`index.html`](index.html) (no Node, npm, CDN scripts, or external fonts).
- **Run locally:** Download or clone the repository and open `index.html` in any modern browser.
- **Publish on GitHub Pages:**
  1. Push `index.html` and `README.md` to your GitHub repository.
  2. Go to **Settings → Pages**, choose **Deploy from a branch**, select your default branch (`main`) and `/ (root)`, and save.
  3. Share the generated `https://<username>.github.io/<repo>/` URL with students.

> **Note on Progress Saving:** Completion milestones, quiz best score, theme preference, and certificate name are saved locally in the student's browser via `localStorage` (not synced across devices or private/incognito sessions). Hosting via GitHub Pages (`https://`) ensures reliable `localStorage` persistence across browser reloads.

---

## Official Agile References

- [The Agile Manifesto](https://agilemanifesto.org/) — Original 2001 statement of the 4 core Agile values.
- [Principles Behind the Agile Manifesto](https://agilemanifesto.org/principles.html) — Official text of the 12 Agile Principles.
- [Agile Alliance — Agile 101](https://www.agilealliance.org/agile101/) — Beginner-friendly overview of Agile concepts and practices.
- [The Scrum Guide](https://scrumguides.org/) — Official definition of the Scrum framework (roles, artifacts, and events).

---

*AI tools were used in this project*
