# Mortality-Assumption-Study
This project develops a preliminary mortality assumption-setting workflow for a synthetic life insurance portfolio.



This project develops a preliminary mortality assumption-setting workflow for a synthetic life insurance portfolio. The workflow combines data preparation, Poisson generalized linear modelling (GLM), model comparison, in-sample calibration and ranking diagnostics, age-band credibility blending, a 2025 reference-year basis, and a preliminary select-and-ultimate structure.

•	A core mortality GLM was expanded with additional risk characteristics. The reported AIC decreased from 14,231.88 for the core model to 14,182.95 for the extended model; these values should only be compared when models are fitted to the same response records.

•	The extended model's reported calendar-year coefficient implied an estimated annual mortality trend of approximately −0.94%, but the coefficient was not statistically significant (p = 0.277). This does not establish a reliable mortality-improvement trend.


•	In-sample decile observed-to-expected results were generally close to 1, with some variation in individual deciles. This is encouraging for an initial fit but is not independent validation.

•	Age-band experience rates were blended with GLM-based rates using a limited-fluctuation credibility formula. A 1% annual improvement was then applied to create illustrative 2026 candidate rates.

•	The preliminary select factors were 0.983 for duration 1 and 0.994 for duration 2 relative to duration 3+. Because these factors were identical across all age bands and were derived from a portfolio-mix prediction exercise, they should be treated as provisional duration adjustments rather than a validated issue-age-specific select table.
Overall conclusion: the exercise demonstrates an end-to-end modelling workflow and produces a useful prototype. Before production use, the analysis requires independent validation, stronger exposure and data checks, a consistent issue-age/attained-age/duration structure, and documented assumption governance.
