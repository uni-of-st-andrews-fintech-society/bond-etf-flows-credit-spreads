# src/

Analysis code. Every test goes through one regression function that takes a
signal, a target, lags and controls, returns coefficients with Newey–West
standard errors, and appends a row to `logs/experiments.csv` on every run.
