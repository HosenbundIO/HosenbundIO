<h1 align="center">Hi 👋, I'm David Ivanov</h1>
<h3 align="center"></h3>

## Open Source

### statsmodels
- [#9819 – ENH: Add order parameter validation to `hannan_rissanen`](https://github.com/statsmodels/statsmodels/pull/9819) (merged Jun 2026)
  Implemented a new `_validate_order_params` helper to catch invalid AR/MA/initial-order combinations in the Hannan-Rissanen ARMA estimator, turning two long-standing `xfail` tests into passing ones. Resolves [#9817](https://github.com/statsmodels/statsmodels/issues/9817).

### scipy
- [#25366 – MAINT: sparse: improve `save_npz` error message for unsupported formats](https://github.com/scipy/scipy/pull/25366) (merged Jun 2026)
  Improved the `NotImplementedError` raised by `save_npz` for LIL/DOK sparse matrices to clearly suggest converting via `.tocsr()` or `.tocoo()` first, and extended tests to cover both matrix and array variants. Resolves [#25305](https://github.com/scipy/scipy/issues/25305).

## Skills
Python · C++ · SQL · PySpark

## Interests
Quantitative Finance · Time Series Analysis · Algorithmic Trading
