# GPIReader & GPI Writer

Garmin GPI Format Reader (Garmin Points of Interest) & Writer

[GPIReader](https://github.com/dkxce/KMZRebuilder/blob/master/GPIReader.cs) & [GPIWriter](https://github.com/dkxce/KMZRebuilder/blob/master/GPIReader.cs) integrated into [KMZViewer](https://github.com/dkxce/KMZViewer) & [KMZRebuilder](https://github.com/dkxce/KMZRebuilder).    
Also in [KMZRebuilder](https://github.com/dkxce/KMZRebuilder) you can create your own GPI files.

[GPIReader](https://github.com/dkxce/KMZRebuilder/blob/master/GPIReader.cs) и [GPIWriter](https://github.com/dkxce/KMZRebuilder/blob/master/GPIReader.cs) интегрирован в [KMZViewer](https://github.com/dkxce/KMZViewer) и [KMZRebuilder](https://github.com/dkxce/KMZRebuilder).    
Также, с помощью [KMZRebuilder](https://github.com/dkxce/KMZRebuilder) вы можете создавать свои собственные GPI файлы.

P.S: [GPI](https://www.gpsbabel.org/htmldoc-1.6.0/fmt_garmin_gpi.html) format is Garmin Points of Interest. This format is using to show objects in Garmin Navigators.   
P.S: [GPI](https://www.gpsbabel.org/htmldoc-1.6.0/fmt_garmin_gpi.html) формат - это точки интереса Garmin, который используется для отображения объектов на навигаторах Garmin.

**Can Make**:
- Multilanguage (EN or any latin, RU or any ciryllic)
- Layers (Categories) & POIs 
- [POI Description](https://github.com/dkxce/KMZRebuilder/blob/master/bin/Debug/gpiwriter_comaddcon_help.txt)
- [POI Comment](https://github.com/dkxce/KMZRebuilder/blob/master/bin/Debug/gpiwriter_comaddcon_help.txt) (load/save from/to desc)
- [POI Address](https://github.com/dkxce/KMZRebuilder/blob/master/bin/Debug/gpiwriter_comaddcon_help.txt) (load/save from/to desc)
- [POI Contact](https://github.com/dkxce/KMZRebuilder/blob/master/bin/Debug/gpiwriter_comaddcon_help.txt) (load/save from/to desc)
- [POI Alert](https://github.com/dkxce/KMZRebuilder/blob/master/bin/Debug/gpiwriter_alert_help.txt) (load/save from/to desc) with sound & trigger options
- POI Bitmap (get/set from/to kml style)
- POI Image (get/set from/to kml style)

[KMZ & GPI files Repository](https://github.com/dkxce/KMZ_FILES)     
[Репозиторий KMZ и GPI файлов](https://github.com/dkxce/KMZ_FILES)     


### STEP-BT-STEP for self-created GPI files

1. Get KMZ files (or make your own with [KMZRebuilder](https://github.com/dkxce/KMZRebuilder))
- https://github.com/dkxce/KMZ_FILES
2. Or get PBF (or OSM) file of your region:
- https://www.openstreetmap.org/export
- https://download.geofabrik.de/
- https://download.openstreetmap.fr/extracts/
- https://download.bbbike.org/osm/bbbike/
- https://download.bbbike.org/osm/
- https://protomaps.com/downloads/osm
- https://wiki.openstreetmap.org/wiki/Planet.osm#Country_and_area_extracts
- https://wiki.openstreetmap.org/wiki/Planet.osm#Regional_extract_sources
3. Or get POI file of your region:
- https://www.openandromaps.org/en/downloads
- https://download.mapsforge.org/pois/
4. Or get MAP (MapsForge) file of your region:
- https://www.openandromaps.org/en/downloads
- https://www.androidmaps.co.uk/
- https://download.mapsforge.org/maps/
- https://ftp-stud.hs-esslingen.de/pub/Mirrors/download.mapsforge.org/maps/
- https://www.freizeitkarte-osm.de/android/en/index.html
5. If you get PBF or OSM file convert it to KMZ with
- [KMZPOIfromOSM](https://github.com/dkxce/KMZPOIfromOSM)
6. Open result file with
- [KMZRebuilder](https://github.com/dkxce/KMZRebuilder)
7. Save needed layers to GPI 
8. Explore with
- [KMZViewer](https://github.com/dkxce/KMZViewer) 
