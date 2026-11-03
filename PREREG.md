# Pre-registration

> **Status: DRAFT SKELETON — not yet registered.** The Lead fills this in during
> Phase 1. The registered version is the commit whose hash is recorded in
> `logs/decisions.md`; that hash goes in the paper's appendix. After that, every
> change is logged in `logs/deviations.md`. Commit the filled-in version before
> any regression runs.

## 1. Claim

One line per direction, phrased so it could be false.

- Forward: _e.g. an AUM-scaled outflow on day t predicts a wider spread on day t+1 (HYG → CDX HY, LQD → CDX IG)_
- Reverse: _e.g. spread changes on day t predict flows on day t+1_

Finding only the reverse is a valid answer.

## 2. Test statistic and rejection rule

## 3. Sample dates

- In-sample:
- Out-of-sample:
- March 2020: in the out-of-sample window, or a separate event study?

Spread measure: CDX, or ICE BofA from FRED (decide in `logs/decisions.md` first, and check how much history FRED provides).

## 4. Every planned test

Include the definition of "stress" (a fixed rule, e.g. top decile of 20-day CDX HY spread change, plus named episodes including March 2020), the flow × stress interaction, and premium/discount to NAV as the alternative signal.

Trial count = ETF pairs × directions × specifications. iTraxx is an extension, not the core.

## 5. Benchmark and cost assumptions

Benchmark: the same model with no flow variable.

## 6. Kill criteria

The Phase 4 result that stops the project and makes it a null-result paper.
