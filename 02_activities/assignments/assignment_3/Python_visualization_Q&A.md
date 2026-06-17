# Visualization 1: Ontario Vital Event Trends, 1994-2023

**Dataset:** Comparative Birth, Death, Marriage data, Ontario Data Catalogue: https://data.ontario.ca/en/dataset/comparative-birth-death-marriage-data/resource/8f40d667-b379-41c6-b929-cdcce6e0ada7. The notebook downloads the official CSV linked from this resource page.

**Software used:** Python in a Jupyter Notebook, with Matplotlib as the main visualization library.

**Intended audience:** Ontario public-service analysts, health-system planners, and residents interested in longer-term demographic patterns.

**Message:** The line chart compares live births, deaths, and marriages from 1994 to 2023. It shows long-term differences between event types, including rising deaths, comparatively stable live births, and lower marriage registrations than births or deaths.

**Design choices:** I used a line chart because the x-axis is an ordered time series. I excluded 2024 and 2025 because the catalogue notes that those years are preliminary. I used three high-contrast colours, direct axis labels, a clear title, and text placed outside the plotting panel so it does not overlap the curves.

**Reproducibility:** The notebook downloads the raw CSV from Ontario's official URL, saves the CSV in `data/`, cleans the numeric columns, filters to 1994-2023, and exports the PNG with `fig.savefig()`. The plotted values are not manually typed into a separate chart-ready summary.

**Accessibility:** The chart uses large fonts, high contrast, descriptive title text, and a legend. Colour helps separate the lines, but the legend and line positions also carry the meaning.

**Impacted communities:** Births, deaths, and marriages describe real events affecting Ontario residents and families. Policy makers could use these patterns to think about service planning, but the chart should not be used to make individual-level claims.

**Feature selection:** I included year, live births, deaths, and marriages because they are the three fields in the selected dataset. I focused on 1994-2023 to show the longer complete period while avoiding preliminary years.

**Underwater labour:** The hidden work included locating a direct CSV resource, checking the data dictionary, excluding preliminary years, cleaning numeric columns, choosing the chart type, and making the figure readable.
