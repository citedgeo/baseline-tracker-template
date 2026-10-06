# Baseline tracker template

A blank CSV for logging a baseline: how often AI answers name and cite a brand before any work starts.
Method: [citedgeo.com/measurement/](https://citedgeo.com/measurement/?utm_source=github&utm_medium=social&utm_campaign=baseline-tracker-template).

How to use it:
1. Write 10 to 30 buyer questions for your category; give each a `prompt_id` and keep the set fixed.
2. Ask each question 3 times in Perplexity and 3 times in Google AI Overviews, in a clean session, with one language and region per market.
3. Log one row per answer: date, market, engine, surface, model (if shown), run number.
4. Mark `brand_named`, `domain_cited` and `recommended` as yes or no; `position` is your rank among listed brands, empty if not listed.
5. `facts_correct`: yes, no, or empty if you are not named. List the linked source domains in `cited_domains`, separated by `;`.
6. Rates: mention rate = rows with brand_named = yes ÷ all rows. Count each engine and each market separately; do not blend them.
7. Delete the two rows marked EXAMPLE before you start. "Example Ltd" is a made-up brand.
8. Re-run the same questions the same way later and compare the rates.

## Further reading

- [How to check if Perplexity and Google AI Overviews mention your business](https://citedgeo.com/insights/check-perplexity-google-ai-overviews-mentions/?utm_source=github&utm_medium=social&utm_campaign=baseline-tracker-template): the 10-minute manual check; this sheet can log its results.
- [Same question, different firms](https://citedgeo.com/insights/same-question-different-firms/?utm_source=github&utm_medium=social&utm_campaign=baseline-tracker-template): why step 2 says 3 runs. We asked Perplexity the same local question twice, hours apart, and the two lists shared 48% of firms on average.

License: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/).

CitedGEO team
