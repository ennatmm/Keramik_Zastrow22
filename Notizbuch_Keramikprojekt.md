# Notizbuch Keramikprojekt
##2019-07-02
* in Recogito Znr_20_1230.tif annotiert
    * in den Annotationen wie von Rainer erwähnt, als Tags auch "SAME AS ZNR_20_1230_römZiffer" genutzt
    * Theoretisch könnte man also nach entsprechender Aufbereitung als Tripel dann einen Graph daraus machen
* Annotationen als csv exportiert (4gkggaln5zdewl.csv)
* csv weiter bearbeitet:
    * die Tags mit SAME AS in einzelene Spalten übertragen
    * die DOI des Zeichenblatts eingetragen
	* Spalten gelöscht: TYPE URI VOCAB_LABEL LAT LNG PLACE_TYPE	VERIFICATION_STATUS COMMENTS
	* Tabelle jetzt wie folgt
	
|UUID_pealgios | ANCHOR | DOI_parent |	File_parent | Link_child | Name |SAME AS  |SAME AS | 
|---  |---  |---  |---	|--- |--- |---  |--- |
|4972dab2-508d-483e-abec-9ebced0bc5c2 |	rect:x=93	y=3648	w=1506	h=611 |	https://doi.org/10.5281/zenodo.2529063 |	Znr_20_1230.tif |	https://recogito.pelagios.org/api/annotation/4972dab2-508d-483e-abec-9ebced0bc5c2.jpg |	ZNR_20_1230_XI |	ZNR_20_1230_XII	
|d4154a28-f0a2-48a1-a6b2-c3b4c6830939 |	rect:x=169	y=242	w=1257	h=696 |	https://doi.org/10.5281/zenodo.2529063 |	Znr_20_1230.tif |	https://recogito.pelagios.org/api/annotation/d4154a28-f0a2-48a1-a6b2-c3b4c6830939.jpg |	ZNR_20_1230_I		
| 30555461-6340-4e81-8be0-e3b20d09be14 |	rect:x=1890	y=3151	w=1585	h=548 |	https://doi.org/10.5281/zenodo.2529063 |	Znr_20_1230.tif |	https://recogito.pelagios.org/api/annotation/30555461-6340-4e81-8be0-e3b20d09be14.jpg |	ZNR_20_1230_XII |	ZNR_20_1230_XI | ZNR_20_1230_I

### Zwischenfazit
* aktuell müssten die einzelnen Annotationen reproduzierbar sein, wenn man sich Bild von Zendodo zieht und über XY Pixel die Positionen sucht.
##2019-07-08
* in recogito Znr_15_1230.tif, Znr_16_1230.tif und Znr_17_1230.tif annotiert
* Backups angelegt von Annotationen + Metadaten von ZNR_15_1230.tif, ZNR_16_1230.tif, Znr_17_1230.tif, ZNR_20_1230.tif