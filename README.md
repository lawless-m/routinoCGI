# routinoCGI
mawk cgi script for producing distances betrween lat/long pairs using OSM

this requires a routino installation https://www.routino.org/

and pbf files processed into nodes.mem files using planetsplit



http://localhost/cgi-bin/route?lat1=53.685335&lon1=-0.416387&lat2=53.479544&lon2=-2.954101

km: 207 mins: 138

http://localhost/cgi-bin/route?json&lat1=53.685335&lon1=-0.416387&lat2=53.479544&lon2=-2.954101

{"km":"207", "mins":"138"}

http://localhost/cgi-bin/route?csv&lat1=53.685335&lon1=-0.416387&lat2=53.479544&lon2=-2.954101

"km","mins
"207","138"
