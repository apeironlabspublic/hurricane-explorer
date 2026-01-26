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

[MIT](https://mit-license.org/)

The MIT License (MIT)

Copyright © 2026 Apeiron Labs, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE
