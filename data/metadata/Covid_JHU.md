- `Title`: County Level COVID-19 Incidence Rate
- `Abstract`: This is the data repository for the 2019 Novel Coronavirus Visual Dashboard operated by the Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE)
- `Spatial Coverage`: United States, OSM [link](https://www.openstreetmap.org/relation/148838#map=3/36.46/-80.16)
- `Spatial Resolution`: Counties
- `Spatial Representation Type`: Vector Polygon
- `Spatial Reference System`: Mercator
- `Temporal Coverage`: 1/22/20-8-1-20
- `Temporal Resolution`: N/A
- `Lineage`: The dataset is provided by Chakraborty and preprocessed in the RStudio for analysis. 
We selected columns that are relevant to our analysis. They are POP_ESTIMA and Confirmed, which we then renamed to pop and cases respectively.
We calculated the COVID rate by dividing cases with the total population. 
Finally, we dropped the geometry of the dataset.
- `Distribution`: The data is publically avalible from the JHU website.
- `Constraints`: The data is open access under the Creative Commons Attribution 4.0 International (CC BY 4.0) by the Johns Hopkins University on behalf of its Center for Systems Science in Engineering. Copyright Johns Hopkins University 2020
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
