# Instagram Engagement Analysis
This repository contains the exploratory data analysis, scheduling optimization, and audience engagement strategy built from organic Instagram post performance profiles as part of the Alfido Tech internship program.

## Task Objective
To systematically clean profile interactions, track distribution channels across temporal dimensions (hours/days), map engagement structures from relational tables, and recommend a corporate content calendar strategy.

## Key Pipeline Sections
1. **Data Preprocessing & Merging:** Extracted data from separate relational spreadsheets (`photos.csv`, `likes.csv`, and `comments.csv`) and combined them into a unified tracking framework using dynamic ID resolution.
2. **Temporal Transformations:** Parsed continuous text timestamps to engineer structured `hour` and `day_of_week` categorical time windows.
3. **Engagement Aggregation:** Calculated explicit transaction metrics per post by aggregating localized interaction volumes (total likes + comments).
4. **Visual Analysis:** Plotted hourly interaction trajectories and weekday distribution metrics to pinpoint ideal publishing frequencies.

## Technology Stack
* Python
* Google Colab
* Pandas & NumPy (Data Structuring & Joining)
* Matplotlib & Seaborn (Data Visualization)
