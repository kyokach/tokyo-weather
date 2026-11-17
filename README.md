# Tokyo weather (JSON)

Tokyo's current weather, refreshed every 20 minutes by a GitHub Actions workflow and published with GitHub
Pages as `weather.json`, for a VRChat world's live weather (VRChat can load text from `*.github.io`).

```json
{"unix": 1763350200, "precip": 0.4, "cloud": 96, "code": 61}
```

- `unix`: observation time (Unix seconds)
- `precip`: precipitation (mm/h)
- `cloud`: cloud cover (%)
- `code`: WMO weather code

Weather data by [Open-Meteo.com](https://open-meteo.com/) (CC BY 4.0).
