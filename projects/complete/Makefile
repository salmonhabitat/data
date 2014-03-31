# by default, create both geojson and shapefile
all: \
		complete.geojson \
		complete.shp

# create geojson from csv
complete.geojson: complete.csv
	csv2geojson $< > $@

# create shapefile from geojson
complete.shp: complete.geojson
	ogr2ogr -f 'esri shapefile' $@ $<
	
# remove generated files
clean:
	rm complete.geojson \
		complete.shp \
		complete.dbf \
		complete.prj \
		complete.shx
