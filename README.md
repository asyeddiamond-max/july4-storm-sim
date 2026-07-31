# July 4, 2026 Connecticut Storm — Interactive Simulator

A standalone, in-browser simulator of the July 4, 2026 Connecticut severe-thunderstorm
outage-and-restoration event. Drag crews / fix-rate / PCAO, toggle rain, and scrub time to
replay the restoration hour by hour over a real map of Connecticut; the plotted points are the
actual, cross-referenced Eversource record.

**▶ Live:** https://asyeddiamond-max.github.io/july4-storm-sim/

Everything runs in the browser (Leaflet is bundled in `index.html`; only the map tiles load from
the network). Inputs are public data — NOAA HRRR wind, HIFLD substations, the 2020 U.S. Census,
and cross-referenced storm reporting.
