# 📍 PinPoint – Find Your PIN Code Instantly

> One tap to know the postal PIN code of your current location.

![PinPoint Logo](logo.png)

## 🚀 Live Demo

🔗 **[mayank2969.github.io/pinpoint](https://mayank2969.github.io/pinpoint/)**

## ✨ Features

- **Instant PIN Code** – Get the postal code of your exact location in seconds
- **Dual API Fallback** – Uses BigDataCloud (primary) + OpenStreetMap Nominatim (fallback) for maximum reliability
- **100% Free** – No API keys, no registration, no cost
- **Privacy First** – Your location data never leaves your device or gets stored
- **Works Globally** – Supports postal codes for India, US, UK, and 180+ countries
- **One-Tap Copy** – Copy the PIN code to clipboard instantly
- **Share** – Share your PIN code & location details via Web Share API or clipboard
- **GPS Accuracy** – Shows GPS accuracy (±Xm) so you know how precise the result is
- **Responsive** – Works beautifully on mobile, tablet, and desktop

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Plain HTML5 + CSS3 + Vanilla JavaScript |
| Location | Browser Geolocation API (`navigator.geolocation`) |
| Reverse Geocoding | BigDataCloud API (primary) |
| Fallback Geocoding | OpenStreetMap Nominatim |
| Hosting | GitHub Pages |

## 📦 Project Structure

```
pincode_finder/
├── index.html    # Main app (all-in-one: HTML + CSS + JS)
├── logo.png      # App logo
└── README.md     # This file
```

## 🔧 Local Development

No build step required. Just open `index.html` in a browser:

```bash
# Option 1: Direct open
open index.html

# Option 2: Serve locally (recommended for geolocation to work)
python3 -m http.server 8080
# Then visit http://localhost:8080
```

> **Note:** Geolocation API requires HTTPS or localhost. It won't work when opening `index.html` directly from the filesystem via `file://` in some browsers.

## 🌐 Deployment (GitHub Pages)

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **main branch, root folder**
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`

## 📡 API Attribution

- **BigDataCloud**: [bigdatacloud.com](https://www.bigdatacloud.com/) – Free client-side reverse geocoding
- **OpenStreetMap Nominatim**: [nominatim.openstreetmap.org](https://nominatim.openstreetmap.org/) – © OpenStreetMap contributors

## 📄 License

MIT License – Free to use, modify, and distribute.
