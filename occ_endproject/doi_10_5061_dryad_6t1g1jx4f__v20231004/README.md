# Global database of cement production assets and upstream suppliers

[https://doi.org/10.5061/dryad.6t1g1jx4f](https://doi.org/10.5061/dryad.6t1g1jx4f)

## Description of the data

This database has been created as part of the GeoAsset programme under the Spatial Finance Initiative (UK Centre for Greening Finance and Investment/University of Oxford) in collaboration with Astraea Inc. For more information about this work, visit [https://www.cgfi.ac.uk/spatial-finance-initiative/geoasset-project/](https://www.cgfi.ac.uk/spatial-finance-initiative/geoasset-project/)

Suggested citation: *Tkachenko, N., Tang, K., McCarten, M., Reece, S., Kampmann, D., Hickey, C., Bayaraa, M., Foster, P., Layman, C., Rossi, C., Scott, K., Yoken, D., Christiaen, C. and Caldecott, B. (2023) Global database of cement production assets and upstream suppliers [Dataset]. Dryad. [https://doi.org/10.5061/dryad.6t1g1jx4f](https://doi.org/10.5061/dryad.6t1g1jx4f)*

Please contact [nataliya.tkachenko@lloydsbanking.com](nataliya.tkachenko@lloydsbanking.com) to inform us about any errors, omissions or other feedback.

The dataset consists of two files: **[1]** SFI-Global-Cement-Database-assets.csv, **[2]** SFI-Global-Cement-Database-suppliers.csv

**Layout and field descriptions of file [1]:**

1. **uid**: Unique identifier for the cement plant
2. **city**: City in which the plant is located
3. **state**: State or province in which the plant is located
4. **country**: Country in which the plant is located
5. **iso3**: Three-letter country code defined in ISO 3166-1 alpha 3
6. **country\_code**: Three-digit country code defined in ISO 3166-1 numeric
7. **region**: Region in which the plant is located
8. **sub\_region**: Subregion in which the plant is located
9. **latitude**: Latitude for the geolocation of the plant (based on WGS84 (EPSG:4326))
10. **longitude**: Longitude for the geolocation of the plant (based on WGS84 (EPSG:4326))
11. **accuracy**: The accuracy of the latitude and longitude
12. **status**: Current plant operating status
13. **plant\_type**: The type of cement plant (Integrated or Grinding)
14. **production\_type**: The production process used to produce the clinker at Integrated plants (Wet or Dry)
15. **confdnc**: Accuracy of production capacity (in cases where numerous values are reported)
16. **capacity**: Total cement production capacity (millions of tons)
17. **capacity\_source**: Source used to obtain the capacity estimate (news media, company website or company disclosure reports)
18. **year**: Year the plant started production
19. **owner\_permid**: PermID of the primary owner of the plant\*
20. **owner\_name**: Name of the primary owner of the plant
21. **owner\_source**: Source reporting the ownership link between the plant and owner
22. **parent\_permid**: PermID of the ultimate parent of the owner of the plant\*
23. **parent\_name**: Name of the ultimate parent of the owner of the plant
24. **ownership\_stake**: The percentage ownership attributed to the parent company if the plant is a joint venture. If the plant is majority owned by a single parent company then this column will be blank ('n/a')
25. **parent\_lei**: Legal Entity Identifier (LEI) of the ultimate parent of the owner of the plant
26. **parent\_holding\_status**: The holding status of the ultimate parent (Private or Public)
27. **parent\_ticker**: The primary ticker for the ultimate parent, if the company is publicly traded
28. **parent\_exchange**: The primary exchange for the ultimate parent, if the company is publicly traded
29. **parent\_permid\_2**: PermID of the 2nd ultimate parent of the owner of the plant\*
30. **parent\_name\_2**: Name of the 2nd ultimate parent of the owner of the plant
31. **ownership\_stake\_2**: The percentage ownership attributed to the 2nd parent company if the plant is a joint venture
32. **parent\_lei\_2**: Legal Entity Identifier (LEI) of the 2nd ultimate parent
33. **parent\_holding\_status\_2**: The holding status of the 2nd ultimate parent (Private or Public)
34. **parent\_ticker\_2**: The primary ticker for the 2nd ultimate parent, if the company is publicly traded
35. **parent\_exchange\_2**: The primary exchange for the 2nd ultimate parent, if the company is publicly traded
36. **sourcing**: Locally sourced, imported or hybrid supply of input production materials
37. **raw\_mtrl**: Typology of raw input materials (limestone, clay, gypsum, sand, coal)
38. **clinker**: Whether clinker was used as an input material

**Layout and field descriptions of file [2]:**

1. **uid**: Unique identifier for the cement plant
2. **facility.country**: Country in which the plant is located
3. **supplier.country**: Country in which facility-supplier (mine) is located
4. **supplier.latitude**: Latitude for the geolocation of the facility-supplier (based on WGS84 (EPSG:4326))
5. **supplier.longitude**: Latitude for the geolocation of the facility-supplier (based on WGS84 (EPSG:4326))

\*PermID is a unique open source identifier for entities, which is provided by Refinitiv. For more details on the open source PermID database please visit [https://permid.org/](https://permid.org/).

Note #1: the 2nd ultimate parent information is only provided if the plant is a joint venture, otherwise no 2nd ultimate parent information is provided.

Note #2: where it was not possible to identify relevant entries, datacells are saved as 'n/a'.

## Sharing/Access information

Link to related publicly accessible dataset:

* [https://www.cgfi.ac.uk/spatial-finance-initiative/geoasset-project/cement/](https://www.cgfi.ac.uk/spatial-finance-initiative/geoasset-project/cement/)