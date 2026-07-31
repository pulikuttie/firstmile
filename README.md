# 🚉 FirstMile

**Park the car, catch the ride, make it to work — every morning.**

FirstMile solves the "first mile" of your commute: it finds your location, shows the
next trains, buses, and trams departing from stops near you (with live delays), plans
door-to-door transit routes to your workplace, and maps public parking nearby so you
know where to leave the car.

**Live app:** https://pulikuttie.github.io/firstmile/

## Features

- 📍 One-tap geolocation, or search any starting point
- 🚏 Live departure board for every stop within ~800 m, auto-refreshing each minute
- 🎯 Door-to-door itineraries to work with boarding times; your workplace is remembered
- 🅿️ Public parking within 1.2 km — free/paid, capacity, opening hours, park & ride
- 🗺️ Everything on an interactive map

Works worldwide — no API keys. Live transit data by [Transitous](https://transitous.org),
parking & maps © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors.

## Run locally

```sh
node server.js   # http://localhost:4173
```

Or just open `index.html` — it's a single self-contained file (note: browser
geolocation needs HTTPS or localhost).
