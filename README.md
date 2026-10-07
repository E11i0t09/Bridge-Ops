# Bridge Ops

I'm not a real Trekkie. I couldn't tell you which deck sickbay is on. But I grew up with TNG and Voyager, and those glowing consoles never left my head. Bridge Ops is the result: rounded bars, no official logos, and a slightly unhealthy love for weather data.

## On the console

| Panel | What it shows |
|---|---|
| Weather | current conditions, 7-day forecast, 24-hour chart |
| Air & health | air quality, UV index, pollen |
| Aviation weather | METAR/TAF for nearby airports and your favourites |
| Flight radar | live traffic, aircraft details, flown track and planned route |
| Situation view | rain radar, weather warnings, river levels |
| System | load with history, audio visualizer |
| Stardate | TNG style |

Dimmer, animation toggle, four colour schemes, English/German, metric/imperial.

## Fits your desktop

Scales from 1080p to 4K and ultrawide. The icon zone keeps a strip on the left free for your desktop icons; columns, column width, row height and taskbar gap are adjustable, with a calibration grid to line everything up.

## Install

1. Download `Bridge-Ops-Lively-Public.zip` from [Releases](../../releases).
2. Drag it into Lively and set it as your wallpaper.
3. On first start, the setup wizard asks for your location. Reopen it anytime with the gear button in the top right.

### Optional: flight radar

The free ADS-B services don't allow requests straight from a wallpaper, so the radar needs a tiny relay. `adsb.php` is included: put it on any web space with PHP and enter its URL in the wizard (see `PROXY-HOSTING.txt`). Without it, everything else works and the center shows the situation view instead.

### Optional: Bridge-Ops-Sensor (Windows)

Adds drive usage, network speed per adapter and VRAM. It runs locally only and never sends anything anywhere. The script isn't digitally signed, so Windows SmartScreen will warn you. That's expected; the source is plain text if you want to check it first.

## Important

**Not for real-world decisions.** METAR/TAF and the flight radar are just for fun, never for flight planning or navigation. For weather warnings, only your national weather service counts.

**No warranty.** All data is shown as is and may be delayed, incomplete or wrong.

**Privacy.** Settings stay on your computer. Your PC talks directly to the services listed in `LEGAL.txt`, which see your IP address and location coordinates. If you host `adsb.php`, the same goes for your server.

**Data:** Open-Meteo, MET Norway, aviationweather.gov, RainViewer, adsb.lol, airplanes.live, DWD and PEGELONLINE. Full credits in `LEGAL.txt`.

## License

© 2026 E11iot, [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/). Use and share unchanged with credit, non-commercially. Several data sources only allow non-commercial use. Data sources and fonts keep their own licenses.

Fan project. Not affiliated with or endorsed by Paramount/CBS. Star Trek, TNG and Voyager are trademarks of their respective owners. All artwork is original.

*Engage.*
