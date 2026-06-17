## What changes are you trying to make?
Add Assignment 3 final project files using Ontario's Comparative Birth, Death, Marriage dataset, including two PNG outputs, written explanations, a Matplotlib Jupyter notebook, and a ggplot2 R Markdown file.

## What did you learn from the changes you have made?
I learned how to create visualizations from a raw downloadable government CSV and why it is important to avoid hidden derived datasets.

## Was there another approach you were thinking about making?
I considered using Bike Share Toronto data, but switched to Ontario vital events data because it is available as one direct CSV and is easier for evaluators to reproduce.

## Were there any challenges?
The main challenge was making the workflow fully transparent and readable; I addressed this by using the official raw CSV URL, keeping text outside the plotting area, and making the notebook/Rmd save the resulting PNGs directly.

## How were these changes tested?
I validated the notebook JSON, checked both PNG outputs, verified the Markdown explanations are under the word limit, and confirmed that the code derives the plotted values from the CSV instead of a hidden summary table.

## Related issue
N/A

## Checklist
- [x] I can confirm that my changes are working as intended
