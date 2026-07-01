# Dew Point Pace Converter

High dew point means your sweat won't evaporate, so the same effort costs you speed. This tool pulls the live dew point for your ZIP code and tells you the pace your body will actually hold.

**Live site:** https://rikkar69.github.io/Dew-Point-Pace-Converter/

## Features

- Live dew point lookup by US ZIP code (via [Open-Meteo](https://open-meteo.com) and [Zippopotam.us](https://zippopotam.us))
- Editable slowdown scale, saved locally in your browser
- Rounds up to the next adjustment level when you're within 2° of it
- Everforest dark/light theme, toggle saved locally

## Tech

Single static HTML file — no build step, no backend, no dependencies beyond two public weather/geocoding APIs.

## Credit

- Default adjustment scale adapted from [RunnersConnect](https://runnersconnect.net/dew-point-effect-running/)
- Heat-stress research: [Mantzios et al., 2022, *Med Sci Sports Exerc*](https://pmc.ncbi.nlm.nih.gov/articles/PMC8677617/)
