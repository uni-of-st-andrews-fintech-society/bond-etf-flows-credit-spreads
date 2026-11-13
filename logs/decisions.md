# Decisions

Every methodology choice: data timing, lags, splits, benchmarks, statistical tests,
data sources. Never edit an old entry; add a correction below it.

Entries this log must eventually hold:

- Bloomberg access confirmed or not, and whether CSV export is allowed (Phase 0)
- Bloomberg vs free-data fallback (iShares shares outstanding × NAV, ICE BofA spreads from FRED), recorded before `PREREG.md` is committed
- `PREREG.md` commit hash (Phase 1)
- Frozen dataset tag, e.g. `data-v1` (Phase 3)
- Go/no-go against the kill criteria (Phase 4)

Template:

```
## YYYY-MM-DD — <short title>
- What:
- Alternatives considered:
- Why:
- Who:
```

---

## 2026-11-13 — Bloomberg access confirmed (Phase 0)
- What: The team has Bloomberg access, and CSV export is allowed.
- Alternatives considered: The free-data fallback in the framework (flows rebuilt from iShares daily shares outstanding × NAV, and ICE BofA corporate spreads from FRED). It is no longer needed for access reasons. Which source the study uses is still to be recorded as its own entry before `PREREG.md` is committed.
- Why: The framework's bond ETF notes say to confirm Bloomberg access first, because it is the project's main data risk.
- Who: alexanderschmidt0111-afk
