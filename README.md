# Predictive Risk Scores Intervention Pre-Post Analysis (Synthetic Data)

This project demonstrates how to model and visualize the impact of an intervention based on predictive risk scores using synthetic student-level risk score data. It includes:

- Simulated data for two groups (Pre vs. Post)
- Longitudinal modeling using mixed effects regression
- Visualization of predicted risk trajectories with confidence bands
- A statistical test comparing model fit with and without group × time interaction

## 📁 Project Structure

PredScorePrePost/
├── PredScorePrePost.Rmd # Main analysis script
├── README.md # This file
├── outputs/ # (Optional) Saved plots or HTML

swift
Copy
Edit

## 📦 Dependencies

The R Markdown file uses the following packages:

- `data.table`
- `dplyr`, `tidyverse`
- `lme4`, `splines`, `ggeffects`
- `ggplot2`, `knitr`, `rmarkdown`

Install everything with:

```r
install.packages(c(
  "data.table", "dplyr", "tidyverse", "lme4", "ggeffects",
  "splines", "ggplot2"
))
▶️ How to Run
Open early_alert_analysis.Rmd in RStudio.

Click Knit to render as an HTML report.

Or run:

r
Copy
Edit
rmarkdown::render("PredScorePrePost.Rmd")
The plot and model summary will appear in the output file.

🔍 Notes
All data is synthetic and fully generated within the script—no real student records were used.

Weekly scores reflect typical early alert risk probabilities from past terms.

Instructor IDs are randomly assigned but could be extended to introduce clustering.

📄 License
MIT License – free to reuse with attribution.

