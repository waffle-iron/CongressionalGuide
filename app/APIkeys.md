#API Keys
##Sunlight
Candidate and legislative bill information is access via the [Sunlight Foundation API](http://sunlightfoundation.com/api/). Apply for a key on that website.

In `/app/public/js/main.js` replace `[apikey]` with your Sunlight API key at the line:

`var SUNLIGHT_APIKEY = '[apikey]';`

##Geocoding

In `/app/public/js/main.js` replace `[apikey]` with your API key at the line:

```
$.ajax('https://geoservices.tamu.edu/Services/Geocode/WebService/GeocoderWebServiceHttpNonParsed_V04_01.aspx', {  
		data: {
            apiKey: '[apikey]'