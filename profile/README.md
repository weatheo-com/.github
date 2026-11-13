# Weatheo

Weatheo publishes weather forecasts, rain radar and air quality for cities worldwide at [weatheo.com](https://weatheo.com), in English, French, German and Chinese. These repositories hold the open-source tools around the site: embeddable badges, UI components, an MCP server and climate datasets.

Le site est aussi disponible en français : [weatheo.com/fr](https://weatheo.com/fr).

Live example, a weather badge for Gien (France):

[![Météo Gien](https://weatheo.com/badge/fr/centre-val-de-loire/gien.svg)](https://weatheo.com/fr/fr/centre-val-de-loire/gien)

## Projects

| Project | What it is | Install / use |
| --- | --- | --- |
| [github-readme-weather](https://github.com/weatheo-com/github-readme-weather) | Live SVG weather badges for READMEs and forums | `https://weatheo.com/badge/<country>/<region>/<city>.svg?style=line` (or `card`; `theme=light\|dark`, `lang`, `units`) |
| [weatheo-ui](https://github.com/weatheo-com/weatheo-ui) | shadcn-style registry of React and Tailwind weather components (WeatheoCard, WeatheoHourly, WeatheoDaily) | `npx shadcn@latest add https://raw.githubusercontent.com/weatheo-com/weatheo-ui/main/public/r/weatheo-card.json` |
| [mcp-server-weatheo](https://github.com/weatheo-com/mcp-server-weatheo) | MCP server (stdio) with the tools `search_places`, `get_weather` and `get_weather_badge` | `npx -y github:weatheo-com/mcp-server-weatheo` |
| [weatheo-icons](https://github.com/weatheo-com/weatheo-icons) | 53 original animated and static SVG weather icons (conditions, moon phases, sunrise/sunset, UV, AQI, pollen), MIT; catalogue at [weatheo.com/en/icons](https://weatheo.com/en/icons) | `https://cdn.jsdelivr.net/gh/weatheo-com/weatheo-icons@main/svg/animated/clear-day.svg` |
| [climate-data](https://github.com/weatheo-com/climate-data) | CSV datasets behind the Weatheo climate reports (ERA5 reanalysis via Open-Meteo and Copernicus), CC BY 4.0, Frictionless datapackage | Download the CSV files or read `datapackage.json` |

Code is MIT-licensed unless stated otherwise.

## JSON API

Free, read-only, CORS-enabled, no key:

- `https://weatheo.com/api/v1/weather?place=fr/centre-val-de-loire/gien&lang=fr`
- `https://weatheo.com/api/v1/search?q=gien`

## Links

- Site: [weatheo.com](https://weatheo.com)
- Weather icons: [weatheo.com/en/icons](https://weatheo.com/en/icons)
- Methodology: [English](https://weatheo.com/en/blog/methodology), [Français](https://weatheo.com/fr/blog/methodology)
- Blog: [English](https://weatheo.com/en/blog), [Français](https://weatheo.com/fr/blog)

Weatheo is published by CODELIO.
