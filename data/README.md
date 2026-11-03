# data/

Download and cleaning scripts only: one script per source, each saving to
`data/raw/`.

`data/raw/` is git-ignored. Bloomberg exports and any other licensed or raw
vendor data live there and are never committed. The top-level `README.md`
explains how to obtain the data without Bloomberg.

Planned sources (Phase 3):

- Bloomberg: daily HYG and LQD price, NAV, shares outstanding and flows; CDX IG and CDX HY
- Controls: S&P 500, VIX, 10-year Treasury yield
- Fallback without Bloomberg: NAV and shares outstanding from the iShares fund pages (flow = change in shares × NAV), and ICE BofA corporate spreads from FRED

The timing table and the one-page audit note also belong here.
