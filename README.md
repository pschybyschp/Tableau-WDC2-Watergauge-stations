# Tableau-WDC-Watergauge
Tableau Webdataconnector Watergaugestations: provides master data data given by REST-API of Pegelonline which is administrated by the Wasser- und Schifffahrtsverwaltung des Bundes - its the german Federal Waterways and Shipping Administration.

The master data for the watergauge stations can be accessed using 
https://www.pegelonline.wsv.de/webservices/rest-api/v2/stations.json

The documentation of the data can be accessed using 
https://www.pegelonline.wsv.de/webservice/dokuRestapi

Its JSON data about the watergauge stations installed in the sea and river landscape of Germany with following structure:

uuid	-     Eindeutige unveränderliche ID         - ID

number	-   Pegelnummer                           - Number of watergauge station

shortname	- Pegelname (max. 40 Zeichen)           - Watergauge name, short

longname -  Pegelname (max. 255 Zeichen)          - Watergauge name, short

km	-       Flusskilometer                        - km of river

agency	-   Wasserstraßen- und Schifffahrtsamt    - agency name

longitude - Längengrad in WGS84 Dezimalnotation   - longitude

latitude -	Breitengrad in WGS84 Dezimalnotation  - latitude

water	-     Angaben zum Gewässer                  - name of water/river

