# Visualization 2: Ontario Vital Event Change, 1994 to 2023

**Dataset:** Comparative Birth, Death, Marriage data, Ontario Data Catalogue: https://data.ontario.ca/en/dataset/comparative-birth-death-marriage-data/resource/8f40d667-b379-41c6-b929-cdcce6e0ada7. The R Markdown file downloads the official CSV linked from this resource page.

**Software used:** R Markdown, using `ggplot2` for visualization.

**Intended audience:** Public-service analysts and students learning how government data can be turned into a focused visualization.

**Message:** The dumbbell chart compares the three vital event types in 1994 and 2023. It shows both the direction and size of change: deaths increased substantially, live births decreased slightly, and marriages changed only modestly.

**Design choices:** I used a dumbbell chart because the goal is to compare two time points for each event type. Grey dots show 1994, blue dots show 2023, and percent-change labels provide the main interpretation without requiring mental calculation.

**Reproducibility:** The R Markdown file downloads the raw Ontario CSV, filters to 1994 and 2023, calculates percent change, reshapes the three event columns into a plotting table, and exports the PNG with `ggsave()`. The plotted values come from the CSV rather than a separate manually summarized plotting file.

**Accessibility:** The figure uses high contrast, large text, direct value labels, and a simple y-axis. The single-colour design avoids relying on colour distinctions.

**Impacted communities:** These registrations relate to Ontario families and to services such as hospitals, public health, civil registration, and social planning. The chart should be interpreted as registration counts, not as a complete explanation of fertility, mortality, or family formation.

**Feature selection:** I selected 1994 and 2023 to compare an early year in the modern dataset with the most recent complete published year. I included all three event types from the selected dataset.

**Underwater labour:** The hidden work included finding a direct CSV, checking the preliminary-year note, choosing a complete recent year, reshaping the data for plotting, and using a simple accessible design.
