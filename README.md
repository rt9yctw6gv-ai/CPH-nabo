# Copenhagen Neighbourhood Finder

A browser-based tool for choosing where to buy a home in Copenhagen and North Zealand. It compares 70 postcode areas by price, school grades, commute, public transport, places to eat and entertainment.

**Open the app:** https://rt9yctw6gv-ai.github.io/cph-nabo/

## Features
- Ranking of 70 postcode areas, weighted by what matters to you (affordability, commute, schools, transport, food, entertainment)
- Budget, size and property type (flat / house) with estimated purchase cost per area
- Commute estimate to your workplace by public transport, bike or car
- Live amenity counts from OpenStreetMap (stations, bus stops, restaurants, bars and culture, parks, schools)
- Import of 9th-grade exam averages from uddannelsesstatistik.dk (CSV or Excel), matched to the schools in each area
- School finder: walking-distance circle and Boligsiden / Boliga searches for the postcodes within reach
- Address checker: paste listing addresses to see walking time to a chosen school, nearest schools and station, commute and nearby amenities
- CSV export

## Data notes
- Price per m² and default school grades are approximate reference estimates. Click a value in the table to replace it with a current figure; edits are stored only in your browser.
- Commute and walking times are estimates from straight-line distance and the nearest stations. Use the Google Maps link in the app for exact routes.
- Listings are not scraped. The app links to the portals' own search pages.

## Running locally
It's a single static file: open `index.html` in a browser. No build step and no server needed.
