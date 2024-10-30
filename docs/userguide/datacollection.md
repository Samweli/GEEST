## Data Collection

how data was collected...

# Data Collection for GEEST Tool

This page provides guidance on finding and collecting relevant data for the GEEST tool, using Saint Lucia as an example. The data sources, layers, and indicators shown here can serve as references when gathering data for other countries.

## Data Sources for Saint Lucia

<table style="border-collapse: collapse; width: 100%; font-size: small;">
  <tr>
    <th style="border: 1px solid black; padding: 1px; text-align: center;"><b>DIMENSION</b></th>
    <th style="border: 1px solid black; padding: 1px; text-align: center;"><b>FACTOR</b></th>
    <th style="border: 1px solid black; padding: 1px; text-align: center;"><b>LAYER</b></th>
    <th style="border: 1px solid black; padding: 1px; text-align: center;"><b>DATA SOURCE/QUERY</b></th>
  </tr>
  
  <!-- Contextual Section with Merged DIMENSION Cell -->

  <tr>
    <td rowspan="3" style="border: 1px solid black; padding: 1px; text-align: center; ">📝CONTEXTUAL</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">🏢Workplace Discrimination</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">WBL 2024 Workplace Index Score</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://wbl.worldbank.org/content/dam/documents/wbl/2024/snapshots/St-lucia.pdf" target="_blank">
        WBL 2024 index score: 83.8
    </a>
</td>

  </tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">⚖️Regulatory Frameworks</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">WBL 2024 Pay+Parenthood Index Score</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://wbl.worldbank.org/content/dam/documents/wbl/2024/snapshots/St-lucia.pdf" target="_blank">
        WBL 2024 index score: Pay 100  and Parenthood 40
    </a>
  </tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">💵Financial Inclusion</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">WBL 2024 Entrepreneurship Index Score</td>
 <td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://wbl.worldbank.org/content/dam/documents/wbl/2024/snapshots/St-lucia.pdf" target="_blank">
        WBL 2024 index score: Entrepreneurship 75
    </a>
  </tr>
  
  <!-- Accessibility Section with Merged DIMENSION Cell -->
  <tr>
    <td rowspan="9" style="border: 1px solid black; padding: 1px; text-align: center; ">🚶ACCESSIBILITY</td>
    <td rowspan="5" style="border: 1px solid black; padding: 1px; text-align: center; ">🚶‍♀️Women's Travel Patterns</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">👶Location of kindergartens/childcare</td>
 <td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://data.humdata.org/dataset/hotosm-saint-lucia-schools" target="_blank">
        Humdata
    </a>
    or
    <a href="https://overpass-turbo.eu/?Q=[out:xml][timeout:25];{{geocodeArea:Saint%20Lucia}}->.area_0;(node[%22amenity%22=%22kindergarten%22](area.area_0);way[%22amenity%22=%22kindergarten%22](area.area_0);relation[%22amenity%22=%22kindergarten%22](area.area_0););(._;>;);out%20body;" target="_blank">
        OSM
    </a>
</td>
</tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">🏫Location of primary schools</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://data.humdata.org/dataset/hotosm-saint-lucia-schools" target="_blank">
        Humdata
    </a>
   or
    <a href="https://overpass-turbo.eu/?Q=[out:xml][timeout:25];{{geocodeArea:Saint%20Lucia}}->.area_0;(node[%22amenity%22=%22school%22](area.area_0);way[%22amenity%22=%22school%22](area.area_0);relation[%22amenity%22=%22school%22](area.area_0););(._;>;);out%20body;" target="_blank">
        OSM
    </a>
</td>
  </tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">🛒Location of groceries</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://overpass-turbo.eu/?Q=[out:xml][timeout:25];{{geocodeArea:Saint%20Lucia}}->.area_0;(node[%22shop%22=%22greengrocer%22](area.area_0);way[%22shop%22=%22greengrocer%22](area.area_0);relation[%22shop%22=%22greengrocer%22](area.area_0););(._;>;);out%20body;" target="_blank">
        OSM
    </a>
</td>
  </tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">💊Location of pharmacies</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://overpass-turbo.eu/?Q=[out:xml][timeout:25];{{geocodeArea:Saint%20Lucia}}->.area_0;(node[%22amenity%22=%22pharmacy%22](area.area_0);way[%22amenity%22=%22pharmacy%22](area.area_0);relation[%22amenity%22=%22pharmacy%22](area.area_0););(._;>;);out%20body;" target="_blank">
        OSM
    </a>
</td>
  </tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">🌳Location of green spaces</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://overpass-turbo.eu/?Q=[out:xml][timeout:25];{{geocodeArea:Saint%20Lucia}}->.area_0;(node[%22leisure%22=%22park%22](area.area_0);node[%22boundary%22=%22national_park%22](area.area_0);way[%22leisure%22=%22park%22](area.area_0);way[%22boundary%22=%22national_park%22](area.area_0);relation[%22leisure%22=%22park%22](area.area_0);relation[%22boundary%22=%22national_park%22](area.area_0););(._;>;);out%20body;" target="_blank">
        OSM
    </a>
</td>
</tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">🚌Access to Public Transport</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">Location of public transportation stops, including maritime</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://overpass-turbo.eu/?Q=[out:xml][timeout:25];{{geocodeArea:Saint%20Lucia}}->.area_0;(node[%22public_transport%22=%22stop_position%22](area.area_0);node[%22public_transport%22=%22platform%22](area.area_0);node[%22public_transport%22=%22station%22](area.area_0);node[%22public_transport%22=%22stop_area%22](area.area_0);node[%22highway%22=%22bus_stop%22](area.area_0);node[%22highway%22=%22platform%22](area.area_0);way[%22public_transport%22=%22stop_position%22](area.area_0);way[%22public_transport%22=%22platform%22](area.area_0);way[%22public_transport%22=%22station%22](area.area_0);way[%22public_transport%22=%22stop_area%22](area.area_0);way[%22highway%22=%22bus_stop%22](area.area_0);way[%22highway%22=%22platform%22](area.area_0);relation[%22public_transport%22=%22stop_position%22](area.area_0);relation[%22public_transport%22=%22platform%22](area.area_0);relation[%22public_transport%22=%22station%22](area.area_0);relation[%22public_transport%22=%22stop_area%22](area.area_0);relation[%22highway%22=%22bus_stop%22](area.area_0);relation[%22highway%22=%22platform%22](area.area_0);node[%22amenity%22=%22ferry_terminal%22](area.area_0);way[%22amenity%22=%22ferry_terminal%22](area.area_0);relation[%22amenity%22=%22ferry_terminal%22](area.area_0););(._;>;);out%20body;" target="_blank">
        OSM
    </a>
</td>
</tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">🏥Access to Health Facilities</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">Location of hospitals and clinics</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://data.humdata.org/dataset/hotosm_lca_health_facilities" target="_blank">
        Humdata
    </a>
    or
    <a href="https://overpass-turbo.eu/?Q=[out:xml][timeout:25];{{geocodeArea:Saint%20Lucia}}->.area_0;(node[%22amenity%22=%22dentist%22](area.area_0);node[%22amenity%22=%22doctors%22](area.area_0);node[%22amenity%22=%22hospital%22](area.area_0);node[%22amenity%22=%22clinic%22](area.area_0);way[%22amenity%22=%22dentist%22](area.area_0);way[%22amenity%22=%22doctors%22](area.area_0);way[%22amenity%22=%22hospital%22](area.area_0);way[%22amenity%22=%22clinic%22](area.area_0);relation[%22amenity%22=%22dentist%22](area.area_0);relation[%22amenity%22=%22doctors%22](area.area_0);relation[%22amenity%22=%22hospital%22](area.area_0);relation[%22amenity%22=%22clinic%22](area.area_0););(._;>;);out%20body;" target="_blank">
        OSM
    </a>
</td>
</tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">🎓Access to Education and Training Facilities</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">Location of universities and technical schools</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://data.humdata.org/dataset/hotosm-saint-lucia-schools" target="_blank">
        Humdata
    </a>
    or
    <a href="https://overpass-turbo.eu/?Q=[out:xml][timeout:25];{{geocodeArea:Saint%20Lucia}}->.area_0;(node[%22amenity%22=%22university%22](area.area_0);way[%22amenity%22=%22university%22](area.area_0);relation[%22amenity%22=%22university%22](area.area_0););(._;>;);out%20body;" target="_blank">
        OSM
    </a>
</td>
</tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">🏦Access to Financial Facilities</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">Location of Banks and other financial facilities</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://overpass-turbo.eu/?Q=[out:xml][timeout:25];{{geocodeArea:Saint%20Lucia}}->.area_0;(node[%22amenity%22=%22bank%22](area.area_0);node[%22office%22=%22financial%22](area.area_0);way[%22amenity%22=%22bank%22](area.area_0);way[%22office%22=%22financial%22](area.area_0);relation[%22amenity%22=%22bank%22](area.area_0);relation[%22office%22=%22financial%22](area.area_0););(._;>;);out%20body;" target="_blank">
        OSM
    </a>
</td>
</tr>
  
  <!-- Place Characterization Section with Merged DIMENSION Cell -->
  <tr>
    <td rowspan="10" style="border: 1px solid black; padding: 1px; text-align: center; ">🌍PLACE CHARACTERIZATION</td>
    <td rowspan="4" style="border: 1px solid black; padding: 1px; text-align: center; ">🚴Active Transport</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">🚸Location of street crossings</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://www.mapillary.com/developer/api-documentation/points" target="_blank">
        Mapillary
    </a>
   or
    <a href="https://overpass-turbo.eu/?Q=[out:xml][timeout:25];{{geocodeArea:Saint%20Lucia}}->.area_0;(node[%22highway%22=%22crossing%22](area.area_0);node[%22railway%22=%22crossing%22](area.area_0);way[%22highway%22=%22crossing%22](area.area_0);way[%22railway%22=%22crossing%22](area.area_0);relation[%22highway%22=%22crossing%22](area.area_0);relation[%22railway%22=%22crossing%22](area.area_0););(._;>;);out%20body;" target="_blank">
        OSM
    </a>
</td>
</tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">🚴‍♀️Location of cycle paths</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://overpass-turbo.eu/?Q=[out:xml][timeout:25];{{geocodeArea:Saint%20Lucia}}->.area_0;(node[%22highway%22=%22cycleway%22](area.area_0);node[%22highway%22=%22track%22](area.area_0);node[%22cycleway%22=%22track%22](area.area_0);node[%22cycleway%22=%22lane%22](area.area_0);node[%22cycleway%22=%22share_busway%22](area.area_0);node[%22cycleway%22=%22shared_lane%22](area.area_0);way[%22highway%22=%22cycleway%22](area.area_0);way[%22highway%22=%22track%22](area.area_0);way[%22cycleway%22=%22track%22](area.area_0);way[%22cycleway%22=%22lane%22](area.area_0);way[%22cycleway%22=%22share_busway%22](area.area_0);way[%22cycleway%22=%22shared_lane%22](area.area_0);relation[%22highway%22=%22cycleway%22](area.area_0);relation[%22highway%22=%22track%22](area.area_0);relation[%22cycleway%22=%22track%22](area.area_0);relation[%22cycleway%22=%22lane%22](area.area_0);relation[%22cycleway%22=%22share_busway%22](area.area_0);relation[%22cycleway%22=%22shared_lane%22](area.area_0););(._;>;);out%20body;" target="_blank">
        OSM
    </a>
</td>
</tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">👣Location of footpaths</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://overpass-turbo.eu/?Q=[out:xml][timeout:25];{{geocodeArea:Saint%20Lucia}}->.area_0;(node[%22highway%22=%22footway%22](area.area_0);way[%22highway%22=%22footway%22](area.area_0);relation[%22highway%22=%22footway%22](area.area_0););(._;>;);out%20body;" target="_blank">
        OSM
    </a>
</td>
</tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">🏘️Block Layout</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://overpass-turbo.eu/?Q=[out:xml][timeout:25];{{geocodeArea:Saint%20Lucia}}->.area_0;(node[%22landuse%22=%22residential%22](area.area_0);node[%22landuse%22=%22commercial%22](area.area_0);node[%22landuse%22=%22industrial%22](area.area_0);node[%22boundary%22=%22administrative%22](area.area_0);way[%22landuse%22=%22residential%22](area.area_0);way[%22landuse%22=%22commercial%22](area.area_0);way[%22landuse%22=%22industrial%22](area.area_0);way[%22boundary%22=%22administrative%22](area.area_0);relation[%22landuse%22=%22residential%22](area.area_0);relation[%22landuse%22=%22commercial%22](area.area_0);relation[%22landuse%22=%22industrial%22](area.area_0);relation[%22boundary%22=%22administrative%22](area.area_0););(._;>;);out%20body;" target="_blank">
        OSM
    </a>
</td>
</tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">🛡️Safety</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">Street lights/Nighttime lights</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://www.mapillary.com/developer/api-documentation/points" target="_blank">
        Mapillary
    </a>
   or
    <a href="https://eogdata.mines.edu/products/vnl/" target="_blank">
        NTL
    </a>
</td>
</tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">⚠️FCV</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">ACLED data</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="mailto:civanescu@worldbank.org">
      mail for ACLED data
    </a>
</td>
</tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">📚Education</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">Percentage of the labor force comprising women with university degrees</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://data.worldbank.org/indicator/SL.TLF.ADVN.FE.ZS?locations=LC" target="_blank">
        WB data
    </a>
</td>
</tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">💻Digital Inclusion</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">Individuals using the Internet (% of population)</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://data.worldbank.org/indicator/IT.NET.USER.ZS?locations=LC" target="_blank">
        WB data
    </a>
</td>
</tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">🌋Environmental Hazards</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">Global Natural Hazards Data</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">Benny</td>
 </tr>
  <tr>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">💧Water Sanitation</td>
    <td style="border: 1px solid black; padding: 1px; text-align: center; ">Water points</td>
<td style="border: 1px solid black; padding: 1px; text-align: center;">
    <a href="https://www.mapillary.com/developer/api-documentation/points" target="_blank">
        Mapillary
    </a>
    or
    <a href="https://overpass-turbo.eu/?Q=[out:xml][timeout:25];{{geocodeArea:Saint%20Lucia}}->.area_0;(node[%22emergency%22=%22fire_hydrant%22](area.area_0);node[%22emergency%22=%22water_tank%22](area.area_0);node[%22amenity%22=%22drinking_water%22](area.area_0);node[%22amenity%22=%22water_point%22](area.area_0);way[%22emergency%22=%22fire_hydrant%22](area.area_0);way[%22emergency%22=%22water_tank%22](area.area_0);way[%22amenity%22=%22drinking_water%22](area.area_0);way[%22amenity%22=%22water_point%22](area.area_0);relation[%22emergency%22=%22fire_hydrant%22](area.area_0);relation[%22emergency%22=%22water_tank%22](area.area_0);relation[%22amenity%22=%22drinking_water%22](area.area_0);relation[%22amenity%22=%22water_point%22](area.area_0););(._;>;);out%20body;" target="_blank">
        OSM
    </a>
</td>
</tr>
</table>

## Potential Data Sources for Other Countries

While the above table showcases data specific to Saint Lucia, similar data can be found for other countries through the following sources:

**World Bank - Women, Business and the Law**: Offers indices on workplace discrimination, regulatory frameworks, financial inclusion, and more, helping to track progress on women’s economic empowerment across countries.

**United Nations Development Programme (UNDP)**: Provides metrics on gender equality, economic participation, and sustainable development, essential for evaluating contextual and place-based factors.

**National Statistics Offices**: Many countries publish gender-disaggregated data, which is crucial for contextual and accessibility insights in specific regions.

**International Labour Organization (ILO)**: Collects data on labor force participation, wage disparities, and workplace regulations by country, supporting the analysis of gender gaps and regulatory environments.

**OpenStreetMap (OSM)**: A valuable open-source platform providing geospatial data, including the locations of educational, healthcare, and financial facilities, as well as transport and green spaces. OSM data can help assess accessibility and environmental factors at a local level.

**Humanitarian Data Exchange (Humdata)**: Maintained by the United Nations Office for the Coordination of Humanitarian Affairs (OCHA), Humdata offers open datasets on schools, health facilities, and other infrastructure, aiding in the geospatial analysis of services critical for accessibility assessments.

**Global Natural Hazards Data**: Provides data on environmental hazards, including earthquakes, floods, cyclones, landslides, fires and others across regions. This data is essential for assessing natural risks and planning in vulnerable areas.

**Mapillary**: A collaborative platform that offers street-level imagery contributed by users worldwide. Mapillary data includes vector data on street crossings, sidewalks, and public lighting, making it useful for place-based and accessibility assessments.


**Instructions for Data Collection**:
- **Query the Source**: Use the query instructions provided in the table to filter and collect specific data.
- **Check Availability for Each Country**: Not all indicators may be available for every country; adapt based on what is accessible.
- **Document Sources and Methods**: Record each source, method, and any specific details relevant to your data collection process.


