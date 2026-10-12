# Week 5 Learning Record

## Completed Tasks

- **Task A — Club file organization:** Reviewed the simulated club planning files and created `club-event-summary.md`. The summary distinguishes draft proposals from approved decisions.
- **Task B v1 — Activity picker:** Created `practice/02-campus-picker/output/index.html` using the provided activity data. Implemented location, time, and energy filters, random selection, empty-result handling, selection history, reset controls, and Chinese/English switching.
- **Task B v2 — Improvement:** Added a summary of the active filters so users can see the current selection criteria. Recorded the change in a separate Git commit.
- **Task D — Review and rejection:** Reviewed the intentionally unsafe simulated plan, identified risks involving file operations, unverified versions, fabricated information, and automatic publication, and proposed safer alternatives.

## Testing and Verification

- Checked that the required task commits appear in the GitHub commit history.
- Tested the activity picker in a browser.
- The expected filter cases to verify are:
  - Indoor / 15 minutes / Low: only A01, A02, A03, or A04 may be selected.
  - Outdoor / 15 minutes / Medium: no matching activity should be displayed.
  - Outdoor / 30 minutes / Medium: only A09 may be selected.
- Checked the filter-summary improvement and language-switching behavior.

## Lessons Learned

- Review requirements before making changes.
- Preserve original data and distinguish drafts from approved decisions.
- Test edge cases instead of checking only one successful example.
- Do not invent missing information or perform risky actions without authorization.
- Use Git commit history to preserve and review changes between versions.

## Repository

https://github.com/ANAN4153/agent-lab-w05

## Evidence

The repository commit history records Task A, Task B v1, Task B v2, and Task D. Required screenshots should be stored in the `evidence/` directory.
