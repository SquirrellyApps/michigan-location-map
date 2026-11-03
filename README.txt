# Michigan Store Location Manager — single-user update

## What this version does
- Flat white Lower Peninsula map with county boundaries and county labels.
- Address search and numbered location pins.
- Location directory with edit/delete controls.
- Three photo categories per location: Building, Setup location, Storage location.
- Uses the device camera or photo library for images on supported phones.
- One-page landscape print/PDF of the map and directory (photos are excluded).
- JSON backup and restore, including photos.
- Attempts to migrate old `miLocationPins` entries from this browser automatically.

## Important storage note
This is the single-user, browser-local version. Locations are saved in browser localStorage and photos in browser IndexedDB on this device/browser only. They are not automatically synchronized to another device or shared with other users. Use **Export backup** regularly.

## Update GitHub Pages
1. Download and unzip this package.
2. Open the `michigan-location-map` repository on GitHub.
3. Open the repository's root folder on the `main` branch.
4. Replace `index.html` with the `index.html` in this ZIP (or upload the replacement and commit it).
5. Commit the change. GitHub Pages should publish it after its normal build delay.
6. Open the live page in Safari and refresh. If it still shows the old app, try a private tab or clear the site's cached data.

No secret keys or admin controls are included. The app uses public CDN and public county GeoJSON data, plus OpenStreetMap Nominatim for address search.
