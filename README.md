![](http://img2.wikia.nocookie.net/__cb20110128060130/alf/images/9/92/Cat_sandwich.jpg)
# ALF
 **ArcGIS** zoom **Level** **Fixer** - Eats Cats And Zoom Levels


---

The goal of this application is to provide an Esri smart proxy that allows the use of AGOL and ArcServer resources with custom zoom levels in tools/applications expecting traditional webmap zoom levels and resolutions

This application does the following:

1. Looks up the ArcGIS MapServer's LOD configuration
2. Compares the zoom level resolutions to the typical [web-map zoom levels](http://services.arcgisonline.com/arcgis/rest/services/World_Street_Map/MapServer) 
3. Redirects the request with a 302 status code to the ArcGIS MapServer with the corrected `z` level


To use:
-----------

1. visit: http://gisinc.github.io/arcgis-level-fixer/
2. Create a proxy/redirect url
3. Use the new url!
 
If you like it:
---

Donate to a pet charity to feed the hungry cats...
:smiley_cat::smile_cat::heart_eyes_cat::kissing_cat::smirk_cat::scream_cat::joy_cat:
