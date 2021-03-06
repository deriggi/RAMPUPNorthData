
![Alt text](Mazar_image_2.png)
# 219,068 Parcel Boundaries for Municipalities in Northern Afghanistan

RAMP UP North's objective was to strengthen municipal governments in the northern part of Afghanistan.
The principal component of this effort involved using a land management system to help government officials  provide better services for their muncipalities.
The data presented here is the output of the the GIS analysts work to demarcate the boundaries of every parcel of property in the municipalities

The data was traced using ArcGIS 10.1 and imagery from USAID's GeoCenter. An effort was made to check data quality pertaining to gaps between adjacent boundaries but some gaps may still exist.  

## Shapefile Downloads 
Separate shapefiles for each municipality are available here. Each file uses the EPSG:4326 projection.

<table>
	<tr><th>Municipality</th>	<th align='right'>Num Parcels</th>  <th align='right'>Download</th> </tr>
    <tr>
        <td>Faizabad</td> 		<td align='right'>11972</td> <td>
        <a href='/municipal_parcels_export/Badakshan'>download</a></td>
    </tr>
    <tr>
        <td>Pul-e Kumri</td> 	<td align='right'>24248</td> <td><a 	href='/municipal_parcels_export/Baghlan'>download</a></td>
    </tr>
    <tr>
        <td>Khulm</td> 			<td align='right'>7925</td> <td><a 	href='/municipal_parcels_export/Balkh'>download</a></td>
    </tr>
    <tr>
        <td>Mazar-e Sharif</td>	<td align='right'>79865</td> <td><a 	href='/municipal_parcels_export/Balkh'>download</a></td>
    </tr>
    <tr>
        <td>Andkhoy</td> 		<td align='right'>9657</td> <td><a 	href='/municipal_parcels_export/Faryab'>download</a></td>
    </tr>
    <tr>
        <td>Maymana</td> 		<td align='right'>13740</td> <td><a 	href='/municipal_parcels_export/Faryab'>download</a></td>
    </tr>
    
    <tr>
        <td>Sheberghan</td> 	<td align='right'>24823</td> <td><a 	href='/municipal_parcels_export/Jawzjan'>download</a></td>
    </tr>
    <tr>
        <td>Kunduz</td> 		<td align='right'>31531</td> <td><a 	href='/municipal_parcels_export/Kunduz'>download</a></td>
    </tr>
    <tr>
        <td>Aybak</td> 			<td align='right'>5210</td> <td><a 	href='/municipal_parcels_export/Samangan'>download</a></td>
    </tr>
    <tr>
        <td>Sar-e Pul</td> 		<td align='right'>9685</td> <td><a 	href='/municipal_parcels_export/Sarepul'>download</a></td>
    </tr>
</table>

 

## The Uses of Parcel Boundaries
The parcel data is applicable to a variety of situations and is probably most valuable to Afghan municipal governments and data practitioners working in Afghanistan. Hopefully, the people of Afghanistan can use the data to simply study and improve the urban areas near where they live.

The data is especially relevant to the field of disaster response. Northern Afghanistan has a [history of earthquakes](http://earthquake.usgs.gov/earthquakes/world/historical_country.php#afghanistan), including two in 1998 in which over 6,000 people lost their lives. With the danger clearly there, accurate urban spatial data could help people plan and respond to natural hazard events in the future.   

After the Haiti earthquake, there was a conspicuous lack of spatial data about building infrastructure. This resulted in an [an incredibly fast construction](http://vimeo.com/9182869) of open spatial data in OSM. Presumably, if first responders had access to this data before the earthquake then the relief effort could have been more efficient

## Working with the data
The easiest way to work with the data is to open it up in your favorite GIS. QGIS is a free tool and works well for anayzing shapefiles. [Download QGIS] (http://www.qgis.org/en/site/forusers/download.html) if you do not already have it on your machine

* Choose one of the files from the table above and download it and unzip it
* Open up QGIS
* Drag the .shp file onto your workspace
![drag .SHP file onto qgis workspace](dragqgis.png)


## A Web Map of the Mazar-e Sharif Data
[Interact with the Mazar-e Sharif Data](http://deriggi.github.io/RUNorthArcPy/mazar/mazar.html)


## Sample Visualisations
Here some sample visualisations to give you an idea of the how the municipalities vary in size and distribution. Each was made with QGIS.

### Mazar-e Sharif
![Alt text](mazar_parcels.png)

### Faizabad
![Alt text](faizabad_parcels.png)

### Pulekhumri 
![Alt text](pulekhumri_parcels.png)

### Khulm
![Alt text](khulm_parcels.png)

### Maymana
![Alt text](maymana_parcels.png)

### Shberghan
![Alt text](shberghan_parcels.png)

### Kunduz
![Alt text](kunduz_parcels.png)

##License
This data is available under the [Creative Commons License](http://creativecommons.org/licenses/by-nc/3.0/)



