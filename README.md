# 🚉 FirstMile

**Park the car, catch the ride, make it to work — every morning.**

FirstMile solves the "first mile" of your commute: it finds your location, shows the
next trains, buses, and trams departing from stops near you (with live delays), plans
door-to-door transit routes to your workplace, and maps public parking nearby so you
know where to leave the car.

**Live app:** https://pulikuttie.github.io/firstmile/

## Features

- 📍 One-tap geolocation, or search any starting point
- 🅿️ Public parking near you, free spots first — capacity, hours, and driving directions
- 🎯 Your 5 best ways to get there, ranked — each pairs the transit route (boarding stop,
  time, arrival) with the best car park at the boarding station, refreshed every minute
- 📍 One-tap geolocation; your destination is remembered for next time
- 🌏 NSW, Australia only (addresses and location are geo-fenced)

No API keys. Live transit data by [Transitous](https://transitous.org),
parking data © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors.

## Run locally

```sh
node server.js   # http://localhost:4173
```

Or just open `index.html` — it's a single self-contained file (note: browser
geolocation needs HTTPS or localhost).
