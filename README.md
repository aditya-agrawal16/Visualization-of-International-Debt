# Visualization-of-International-Debt
This project tries to visualise an economic problem of the debt taken by different countries from the World Bank. We are going to visualize and analyse international debt data collected by The World Bank. The dataset contains information about the amount of debt (in % of their GDP) owed by developing countries across several categories. The dataset contains both national and regional debt statistics for several countries across the globe as recorded from 1950 to 2018.

Implementation Aspects:
1. Take CSV file from International Monetary Fund as data input.
2. Process this data file using ‘panda’ library of python. This gives us a processed dataset.
3. We have used ‘seaborn’ library of python to plot the change in debt. We will also fit regression model to this change in debt of some selected countries.
4. Now, to plot a geospatial map, we use the dataset processed by panda and merge it with a shapefile using geopanda library.
5. This merged file is then converted to GeoJSON format.
6. Finally, using this GeoJSON file as input, we plot a geospatial map using bokeh library.
