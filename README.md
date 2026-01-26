# Hurricane Data Explorer

Interactive visualization of NOAA HURDAT2 hurricane data.

## Features

- 🌀 Browse Atlantic and East Pacific storms (1851-present)
- 🔍 Search storms by name with autocomplete
- 📊 Rapid intensification analysis with decade comparison charts
- 🗺️ Click anywhere on map to find nearby historical storms
- ⏱️ Timeline scrubber to animate storm progression
- 📷 Export maps as PNG with legend
- 📊 Export filtered data as CSV
- ⏱️ Weekly check for new data from NOAA's HURRDAT for Atlantic and Pacific data and update.

## Data Updates

Storm data is automatically updated weekly from NOAA via GitHub Actions.

## Local Development

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/hurricane-explorer.git
cd hurricane-explorer

# Serve locally
python -m http.server 8000

# Open http://localhost:8000
```

## Data Source

[NOAA National Hurricane Center HURDAT2](https://www.nhc.noaa.gov/data/#hurdat)

## License

MIT
