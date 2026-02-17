**Dataset:** TTC LRT Delays  
**Source:** City of Toronto Open Data Portal  
**URL:** https://open.toronto.ca/dataset/ttc-lrt-delay-data/

Average TTC LRT Delay by Line

Software Used
This visualization was created using Python, specifically pandas for data manipulation and matplotlib for plotting. Python was chosen to ensure full reproducibility and transparency of the analysis.

Intended Audience
The intended audience includes TTC riders, City of Toronto policymakers, and transit planners interested in understanding route-level reliability.

Message Conveyed
This visualization shows the average delay duration for each TTC LRT line. It highlights differences in service reliability across routes, allowing viewers to quickly identify which lines experience longer average delays.

Design Considerations
A bar chart was selected for clarity and ease of comparison. Axis labels and a descriptive title were added to ensure interpretability. No colour encoding was required, reducing visual clutter and improving accessibility.

Reproducibility
The visualization is fully reproducible using the provided Python script. Any user with access to the dataset can regenerate the figure and validate the results.

Accessibility
The chart uses clear labels, sufficient font sizes, and avoids colour-dependent encoding. The figure can be interpreted without relying on colour vision.

Impacted Communities
Daily commuters, shift workers, students, and individuals with mobility constraints may be disproportionately affected by delays on specific LRT lines.

Feature Selection
Only the LRT line identifier and delay duration were used to keep the visualization focused on route-level reliability.

Underwater Labour
Data cleaning, aggregation, verification of delay metrics, and iterative design choices contributed significantly to the final visualization.
