# ☕ Coffee Quality Analysis using Power BI

This project explores the Coffee Quality Institute (CQI) dataset to uncover insights into what influences the sensory quality of coffee. We address four research questions using visual analysis in Power BI.

---

## 📌 Research Objectives

1. Identify key determinants of coffee quality based on sensory attributes (aroma, flavor, acidity, etc.).
2. Explore correlations between processing methods, origin regions, and overall quality scores.
3. Detect trends in defect types and their impact on quality evaluation.
4. Understand how multiple variables interact to influence Total Cup Points — the overall quality score.

---

## 📊 Tools Used

- **Power BI**: for data visualization and dashboarding
- **DAX**: to build calculated columns and KPIs
- **Excel / CSV**: for initial data inspection and cleanup

---

## 🖥️ Dashboard Features

- Interactive filters for origin, processing method, and grading scores
- Trend analysis of Total Cup Points and sensory variables
- Heatmaps and slicers for multivariable interaction
- Custom DAX measures for KPI display

---

## 📁 Repo Contents

- df_arabica.csv : which is the original unprocessed dataset on which the preprocessing of imputation and empty value removal was done pre-analysis stage.
- Coffee_quality_final.pbix : represents the dashboard containing all the visuals, filters and slicers for dynamic visualizations.
- Report: consists of all the consolidated findings to the research question from observations and trends in the dataset as visualized by the dashboard in detail.

## 📈 Insights Summary

- Balance, aftertaste, and flavor strongly correlate with Total Cup Points.
- Double Anaerobico Washed processing tends to yield higher average scores in certain areas.
- Certain origin regions consistently show quality advantages.
- Defects like sour and moldy beans negatively influence overall scores.
