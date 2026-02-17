**Dataset:** TTC LRT Delays  
**Source:** City of Toronto Open Data Portal  
**URL:** https://open.toronto.ca/dataset/ttc-lrt-delay-data/

Most Common TTC LRT Delay Causes

# Visualization 2 (Non-Python Tool): Most Common TTC LRT Delay Causes

## Software used
This visualization was created in Excel. The chart is based on the same TTC LRT delays dataset, enhanced using the provided delay code descriptions.

## Intended audience
General TTC riders and non-technical stakeholders (community members, city staff) who want to understand the most common reasons for LRT delays.

## Message / what it conveys
This chart shows the top 10 most frequent delay causes. It shifts the focus from “which line is delayed” to “why delays happen,” supporting operational and communication priorities.

## Design considerations (and how applied)
- **Chart type:** Bar chart for comparing category frequencies.
- **Sorting:** Categories are sorted by frequency (descending) so the most common causes are immediately visible.
- **Readable labels:** Used human-readable delay cause descriptions (not raw codes) for accessibility.
- **Layout:** Rotated/adjusted labels to prevent overlap and preserve readability.

## Reproducibility (and limitations)
Excel is less reproducible than code-based workflows because steps are often manual (pivot table creation, sorting, chart formatting). To mitigate this:
- The raw datasets are included in the repo.
- The Excel file (or a documented set of steps) records how the chart was produced.
- A Python appendix notebook documents the merge logic between delay codes and descriptions.

## Accessibility
The visualization uses clear labeling, avoids meaning conveyed solely by color, and presents categories in a simple, interpretable format.

## Communities impacted
Frequent delay causes can affect rider trust and commute planning. Riders with limited scheduling flexibility (shift workers, caregivers) and riders requiring predictable accessible transit may be impacted most.

## Feature inclusion/exclusion
Included delay causes (code descriptions) and incident counts. Excluded finer breakdowns (by station/time) to keep the chart focused and understandable.

## Underwater labour
Matching codes to descriptions, ensuring consistent categorization, cleaning text labels, and validating counts across tools were necessary to produce an interpretable visualization.
