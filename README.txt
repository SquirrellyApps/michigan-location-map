Michigan Location Map — iPhone-compatible hosting package

WHY THE MAP MAY LOOK BLANK
The ChatGPT/iOS file preview does not reliably run interactive HTML/JavaScript apps. This map uses Leaflet, online map tiles, and address geocoding, so it needs to run in a full browser or be hosted as a website.

QUICKEST TRY ON IPHONE
1. Download michigan_location_map.html to the Files app.
2. If tapping it opens a static preview, use Share > Open in Safari if that option is offered.
3. If it still does not run, host the file as a website using the steps below.

HOST IT WITH GITHUB PAGES
1. On GitHub, create a new public repository named michigan-location-map.
2. Upload michigan_location_map.html and rename it to index.html.
3. Open the repository's Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch, select the main branch and /(root), then Save.
5. Wait for GitHub Pages to publish; the site URL will look like https://YOUR-USERNAME.github.io/michigan-location-map/
6. Open that website in Safari. Add the site to your Home Screen if desired.

FEATURES
- Starts with no pins.
- Add a location name and address to geocode and create a labeled pin.
- County boundaries and county labels are loaded from public GeoJSON data.
- Location directory, remove pin, CSV export, and print/save as PDF.
- Pins are saved in the browser's local storage. They are specific to that browser/device unless exported.

NOTES
- Requires internet access for Leaflet, map tiles, county GeoJSON, and address lookup.
- When printing, choose Landscape and fit to one page.
