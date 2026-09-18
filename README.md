![header](https://sorrego.net/wp-content/uploads/multimodal-header.jpg)

# Multimodal Research in Spain

An interactive map documenting researchers, PhD candidates, groups, and projects working on multimodal research in Spain.

The map is built from a CSV dataset and rendered dynamically using JavaScript and Leaflet.

**Access the map here -->** https://sorregoxyz.github.io/multimodal-research-spain/  

Locations are approximate, at city level, not exact addresses. When several nodes share a city, they're spread out visually around it so they can be told apart; that spread is a visual device only and doesn't indicate a distinct real position.


### Info
> This project uses CARTO for layering the basemap. Recently, CARTO has started requiring an API key for their free tiles. This version has its own API linked to three pages where the map is currently published. If you want to use this map in your project and to ensure a correct display, please get your own API key at https://carto.com/basemaps/apikey and then replace the existing one. Search for the following line:

> `L.tileLayer('https://{s}.basemaps.cartocdn.com/light_all/{z}/{x}/{y}{r}.png?key=YOUR_KEY', { attribution: '&copy; OpenStreetMap contributors &copy; CARTO', subdomains: 'abcd', maxZoom: 19 }).addTo(map);`

## Structure

- `index.html` — interactive map
- `data/data_multimodality.csv` — dataset
- `LICENSE`

The project is continuously updated as new researchers, PhD candidates, and initiatives are identified.

Contributions and corrections are welcome.
