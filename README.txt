IRUVADA VILLAGE LAND MAP - PROTOTYPE

Files:
- index.html: mobile map prototype
- land.geojson: 2,871 valid parcel geometries converted from the supplied CSV

Features:
- OpenStreetMap and satellite background switch
- GPS blue marker and accuracy circle
- Point-in-polygon LP detection
- Search LP / survey / khata
- Parcel popup with available fields

IMPORTANT:
This is a prototype. The GeoJSON is loaded by the browser, so a technically skilled visitor could retrieve it even though there is no download button. For a production version with Google login and private owner details, keep owner data server-side (e.g. PostGIS/Supabase) and return only the parcel selected by an authenticated user.

The satellite layer in this prototype uses Esri World Imagery. OSM is used for the street/map layer. Replace/add a georeferenced drone GeoTIFF through a tile/COG service in the production version.
