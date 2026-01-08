## Adding sentinal images to missions.yml

- Login to https://browser.dataspace.copernicus.eu/ and select a polygon of the area
- Copy the coordinate extents 
- Download as geotiff EPSG3857: web mercator
- Open in QGIS and change symobology to singleband gray
- Project > Import/Export > Export map as image and save as .png file
- Upload to a subfolder on this repository
- Add a line in the missions.yml file with a link to this repo
e.g.
sentinal-2-28thDec2025: { type: image, url: "https://lewisdrysdale.github.io/leaflet-assets/images/sentinal2_ryderbay.png", extents: [-67.62, -68.45, -67.50, -68.03] }


