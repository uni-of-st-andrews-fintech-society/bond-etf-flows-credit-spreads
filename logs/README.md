# logs/

If it isn't logged, it didn't happen. These files prove the question came before
the answer and show how many things were tried.

| File | Write down | Why it matters |
|---|---|---|
| `experiments.csv` | Every run, including failures: date, commit hash, parameters, data version, in- or out-of-sample, headline result | The true trial count for the multiple-testing correction |
| `decisions.md` | Each methodology choice: date, what, alternatives, why, who | Reviewers check reasoning, not just results |
| `deviations.md` | Any change to `PREREG.md` after Phase 1, and whether results had been seen | Separates planned tests from post-hoc ones |
| `ai-log.md` | Load-bearing AI use: date, task, what a human verified | Feeds the AI disclosure in the paper |
| `meetings.md` | Attendees, decisions, actions, owners | Keeps the whole team aligned |

Rules:

- Log the same day, and commit logs together with the code they describe.
- Never edit an old entry. Add a correction below it.
- New entries go at the bottom of each file.
