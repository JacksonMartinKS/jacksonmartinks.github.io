# Jackson Martin Forecasts

Landing page for https://jacksonmartinks.github.io/ - links to the model sites:

- NFL 2026: https://jacksonmartinks.github.io/2026-nfl-model/
- Kansas House 2026: https://jacksonmartinks.github.io/2026-ks_state-house-model/

The preview cards load live numbers from those two sites on page load
(`/2026-nfl-model/forecast-data.js`, `/2026-ks_state-house-model/overall_forecast.json`,
`seat_distribution.csv`), so they update whenever the model repos are pushed. A snapshot
from the build date is baked into `index.html` as a fallback.

`404.html` is the custom not-found page for the domain.
