URL of WMS GetCapabilities request: https://friendly-enigma-wrgx44945v5vhqqq-8080.app.github.dev/geoserver/ows?service=WMS&version=1.3.0&request=GetCapabilities

URL of WFS GetCapabilities request: https://friendly-enigma-wrgx44945v5vhqqq-8080.app.github.dev/geoserver/ows?service=WFS&acceptversions=2.0.0&request=GetCapabilities

![alt text](image-1.png)

Drawing order refers to the way the layers are arranged. Opposite from ArcGIS Pro, the first layer in the drawing order will show up underneath all the others. If the DEM is moved from first to third position, it will cover up layers such as the streams layer. Therefore the DEM must be in first position.