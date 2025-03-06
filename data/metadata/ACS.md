- `Title`: County Level Poverty and Disability Data, Derived from 2014-2018 American Community Survey 5-year Estimates
- `Abstract`: This dataset documents poverty and disability data on the county level. The US Census Bureau collects the data in order to produces information on social, economic, housing, and demographic characteristics about the nation's population every year, which provides an important tool for communities to use and see how they are changing. 
- `Spatial Coverage`: United States, OSM [link](https://www.openstreetmap.org/relation/148838#map=3/36.46/-80.16)
- `Spatial Resolution`: Specify the spatial resolution as a scale factor, description of the level of detail of each unit of observation (including administrative level of administrative areas), and/or or distance of a raster GRID size
- `Spatial Representation Type`: Specify the model of spatial data representation, e.g. one of `vector`, `grid`, `textTable`, `tin` (triangulated irregular network), etc. If the type is `vector`, also specify the geometry type as in the OGC Simple Feature Access standard (https://www.ogc.org/publications/standard/sfa/) , e.g. `POINT`, `LINESTRING`, `MULTIPOLYGON`, etc. 
- `Spatial Reference System`: Specify the geographic or projected coordinate system for the study
- `Temporal Coverage`: 2014-2018
- `Lineage`: We computed the summary statistics, including the min, max, mean, and standard deviation. We processed the data after retrieving it by excluding states that irrelevant to our study area. We also checked for data duplication and omission: we found one county with missing disability and poverty data, for which we replaced the missing data with zeros.
- `Distribution`: The data is avalible for download from the US Census
- `Constraints`: The US Census Data is open access in the public domain. 
- `Variables`: For each variable, enter the following information. If you have two or more variables per data source, you may want to present this information in table form (shown below)
  - `Label`: variable name as used in the data or code
  - `Alias`: intuitive natural language name
  - `Definition`: Short description or definition of the variable. Include measurement units in description.
  - `Type`: data type, e.g. character string, integer, real
  - `Accuracy`: e.g. uncertainty of measurements
  - `Domain`: Expected range of Maximum and Minimum of numerical data, or codes or categories of nominal data, or reference to a standard codebook
  - `Missing Data Value(s)`: Values used to represent missing data and frequency of missing data observations
  - `Missing Data Frequency`: Frequency of missing data observations: not yet known for data to be collected

| Label | Alias | Definition | Type | Accuracy | Domain | Missing Data Value(s) | Missing Data Frequency |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| variable1 | ... | ... | ... | ... | ... | ... | ... |
| variable2 | ... | ... | ... | ... | ... | ... | ... |
