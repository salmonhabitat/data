# by default, create both geojson and shapefile
all: \
		wes-ashe-masters.geojson \
		wes-ashe-masters.shp

# create geojson from csv
wes-ashe-masters.geojson: wes-ashe-masters.csv
	csv2geojson $< > $@

# create shapefile from geojson
wes-ashe-masters.shp: wes-ashe-masters.geojson
	ogr2ogr -f 'esri shapefile' $@ $<
	
# remove generated files
clean:
	rm wes-ashe-masters.geojson \
		wes-ashe-masters.shp \
		wes-ashe-masters.dbf \
		wes-ashe-masters.prj \
		wes-ashe-masters.shx
