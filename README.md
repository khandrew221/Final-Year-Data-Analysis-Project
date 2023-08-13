# Final Year Data Analysis Project

A final year project investigating two datasets for connections, worked and presented using **Python** (inc. pandas, NumPy, matplotlib, and folio libraries) and **Jupyter** notebooks. A third data set (UK regional border GeoJSON polygons) was then required for the purposes of presenting the data. The datasets were acquired from the UK government (gov.uk). The questions, methods and datasets were a personal choice within the constraints of having to compare two datasets and incorporate k-means clustering.

## Skills Demonstrated

- JSON data acquisition via a public API 
- Data cleaning and shaping
- Data analysis
- Data mining via k-means clustering
- Data presentation

## Report Summary

This project examines links between attainment at Key Stage 4 (GCSE or equivalent) and overall deprivation as measured by the Index of Multiple Deprivation (IMD), with a focus on attainment in English and Maths.  Five broad types of deprived area at the upper local authority level have been identified using k-means clustering on IMD subdomain data.  The Key Stage 4 (KS4) data focused on three areas: overall high attainment, overall pass attainment, and high attainment in Maths and English.  This data was then combined with overall deprivation and the identified deprivation types to answer the following questions:

1. Does attainment at KS4 in an area correlate to the area's overall deprivation?
2. If so, is this affected by level of attainment?
3. Does attainment in English and Maths have a disproportionate effect on these correlations?
4. Which geographical areas would benefit from a focus on helping educational attainment at KS4?
5. Would these areas benefit from a push to high attainment, a focus on basic pass level attainment, and/or from focus on English and Maths specifically?

In short, the answers to these questions are:

1. Yes. Wider attainment at KS4 reasonably correlates to lower levels of deprivation.
2. No. Where effects are apparent, it is at the level of passing GCSEs or equivalent. 
3. There is a small but clear effect of English and Maths attainment on correlations to IMD.
4. Only the most overall deprived areas.  Areas with medium deprivation are comparable in KS4 attainment to the least deprived areas.
5. The focus should be on students achieving passes, particularly in Maths and English.

The complete report can be found in EMA.odt
