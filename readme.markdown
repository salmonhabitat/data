share-data
==========

Available datasets
------------------

**SHRU, Critical Habitat, and HUC12 watershed boundaries**

This is just a convenience layer. Bundled up the SHRU, Critical Habitat, and HUC 12 watershed boundaries into a single, giant, layer.

Fields: __critical, hu_10_name, hu_12_name, huc_10, huc_12, huc_8, shru, created_at, updated_at__

Downloads: [JSON](http://jacques.cartodb.com/api/v2/sql?q=SELECT%20*%20FROM%20boundaries), [GeoJSON](http://jacques.cartodb.com/api/v2/sql?q=SELECT%20*%20FROM%20boundaries&format=geojson), [SHAPEFILE](http://jacques.cartodb.com/api/v2/sql?q=SELECT%20*%20FROM%20boundaries&format=shp)

**Completed projects**

All of our completed restoration projects. Includes culvert replacements, bridges, and decommissions!

Fields: __bank_calc, bank_est, culvert_co, drainage, focusarea, height, length, owner, share_id, site, status, total_cost, type, upstream, usfws_id, width, x, y, created_at, updated_at__

Downloads: [JSON](http://jacques.cartodb.com/api/v2/sql?q=SELECT%20*%20FROM%20crossings), [GeoJSON](http://jacques.cartodb.com/api/v2/sql?q=SELECT%20*%20FROM%20crossings&format=geojson), [SHAPEFILE](http://jacques.cartodb.com/api/v2/sql?q=SELECT%20*%20FROM%20crossings&format=shp)

**Historic features**

The locations and descriptions of historic features we've found/stumbled across in Downeast Maine. Most are remnants from the log-drive era. Includes features like remnant dams, wingwalls, and mills.

Fields: _comments, completed, condition, dam_id, focusarea, name, passage, reference, source, type, waterbody, x, y, created_at, updated_at__

Downloads: [JSON](http://jacques.cartodb.com/api/v2/sql?q=SELECT%20*%20FROM%20historic), [GeoJSON](http://jacques.cartodb.com/api/v2/sql?format=geojson&q=SELECT%20*%20FROM%20historic), [SHAPEFILE](http://jacques.cartodb.com/api/v2/sql?format=shp&q=SELECT%20*%20FROM%20historic)

**Large Woody Debris projects**

Both our study and production large woody debris additions.

Fields: __contact, efish, id, longpro, notes, owner, shelter, stocked, treatment, trib, type, utm_cbx, utm_cbt, utm_ctx, utm_cty, utm_tbx, utm_tby, utm_ttx, utm_tty, watershed, created_at, updated_at__

Downloads: [JSON](http://jacques.cartodb.com/api/v2/sql?q=SELECT%20*%20FROM%20lwd), [GeoJSON](http://jacques.cartodb.com/api/v2/sql?q=SELECT%20*%20FROM%20lwd&format=geojson), [SHAPEFILE](http://jacques.cartodb.com/api/v2/sql?q=SELECT%20*%20FROM%20lwd&format=shp)

**Temperature loggers**

Most of Downeast Maine has been blanketed with temperature loggers thanks to Scott Craig at the MEFRO office. Many of these are no longer active locations, but at some point, data was collected at each point.

**Wes Ashe Study Sites**

Project locations for our man Wes Ashe's Masters 'First-Summer Survival and Growth of Juvenile Atlantic Salmon in Headwater Streams: Implications for Restoring Connectivity at Road Culverts'.
