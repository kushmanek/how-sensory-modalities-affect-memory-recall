📚 How Sensory Modalities Affect Memory Recall
This repository contains the full analysis and experimental design for a STAT 453 course project conducted in Winter 2025 at the University of Victoria.

📌 Project Overview
The goal of this project was to investigate whether memory recall differs significantly based on how information is presented: visually, auditorily, or through a combined audiovisual approach.

Understanding the effect of sensory modalities on memory has important implications for designing effective learning tools and educational content.

👥 Team Members
Kush Manek 

Eric Huber

Amritpal Singh

Supervisor: Dr. Michelle Miranda

🧪 Experimental Design
Design Type: Randomized Complete Block Design (RCBD)

Treatments:

Visual (view a list)

Audio (hear a list)

Audiovisual (see and hear a list)

Blocks: Gender (Male, Female)

Response Variable: Number of grocery items correctly recalled (0–10)

Sample Size: 30 observations per treatment group

🧮 Statistical Analysis
Conducted using R with dplyr and ggplot2

Analysis of Variance (ANOVA) tested for treatment effects

Additional diagnostics:

Normality: Shapiro-Wilk test & Q-Q plot

Homoscedasticity: Residuals vs. fitted plot

Autocorrelation: Residuals vs. order plot

Post-hoc: Tukey HSD for pairwise comparisons

📊 Results Summary
No significant difference found between the three sensory treatments (p > 0.05)

Tukey HSD confirmed that none of the pairs differed significantly

Residuals showed some deviation from normality but met other ANOVA assumptions

📘 Conclusion
Although no treatment was found to significantly outperform the others, this study:

Demonstrated a rigorous application of RCBD in real-world psychological testing

Suggests that short-term memory recall may not be strongly influenced by modality alone

Provides groundwork for future studies on long-term memory or with broader demographic samples

.
├── README.md               # This file

├── finalreport.pdf         # Full project report

├── combined_data.csv       # Raw data (not included here)

├── analysis_script.R       # R code for data analysis

🧠 Future Work
Expand sample size and demographic diversity

Explore long-term memory effects

Integrate emotional cues and contextual relevance in stimuli

Use more advanced models like mixed-effects or Bayesian approaches

📚 References
See the final report for full academic references.

