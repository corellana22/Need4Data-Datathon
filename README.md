# Team Tam Slam | Need4Data Datathon Fall 2026

## Project Overview

Welcome to **Team Tam Slam's Need4Data Datathon project!**

Our team analyzed a sample of **500,000 U.S. traffic accident records from 2016–2023** to explore how weather conditions, time of day, geographic location, and roadway infrastructure are associated with traffic accident severity.

Our goal was to identify meaningful patterns in traffic disruptions and communicate our findings through data cleaning, exploratory data analysis, and visualization.

## Research Question

**How do weather conditions, temporal patterns, geographic factors, and roadway infrastructure relate to traffic accident severity across the United States?**

## Dataset

Our analysis uses a sample of 500,000 records from the U.S. Accidents dataset, covering 2016–2023.

We examined four primary categories:

- **Weather:** Temperature, precipitation, visibility, humidity, and weather conditions.
- **Time:** Accident start times, end times, and hourly patterns.
- **Geography:** Cities, counties, states, and geographic distribution.
- **Infrastructure:** Traffic signals, junctions, crossings, and other roadway features.

Accident severity represents the reported impact on traffic disruption rather than the severity of injuries.

## Methodology

Our workflow consisted of:

1. Cleaning and preprocessing the relevant variables.
2. Handling missing values and standardizing categories.
3. Exploring each category through descriptive statistics and visualizations.
4. Integrating the cleaned data into a master dataset.
5. Interpreting patterns, limitations, and potential traffic safety implications.

The integrated dataset contains **500,000 observations and 31 columns**.

## Key Findings

Our exploratory analysis identified differences in accident severity across weather categories, along with patterns related to time, geography, and roadway infrastructure.

For example, approximately **22.6% of accidents occurring in rainy conditions were classified as high severity**, compared with approximately **17.2% under clear conditions**.

These findings describe associations within the recorded accident data. They do not establish that a particular condition causes accidents or increases the probability of an accident occurring.

## Repository Structure

```text
Need4Data-Datathon/
│
├── Notebooks/
│   ├── Geographic Notebooks/
│   ├── Infrastructure Notebooks/
│   ├── Time Notebooks/
│   └── Weather Notebooks/
│
├── car_data/
│   └── final_cleaned_data/
│       └── final_cleaned_data.ipynb
│
├── descriptive_statistics_car_data.ipynb
├── Team Tam Slam Slides.pdf
├── Team Tam Slam_Project Synopsis.pdf
├── README.md
└── requirements.txt
```

Each category folder contains notebooks for cleaning, analysis, or visualization.

## Reproducing the Analysis

The large CSV datasets are excluded from GitHub to keep the repository lightweight.

To reproduce the analysis:

1. Obtain the original U.S. Accidents dataset and prepare the 500,000-record sample used in this project.
2. Install the Python dependencies listed in `requirements.txt`.
3. Run the relevant data-cleaning notebooks.
4. Run `car_data/final_cleaned_data/final_cleaned_data.ipynb` to integrate the cleaned datasets.
5. Run the visualization and descriptive statistics notebooks.

Some notebook file paths may need to be adjusted for your local environment.

## Team Members

**Team Tam Slam**

- **Chris Orellana** — Weather analysis and dataset integration
- **Alan** — Time and severity analysis
- **Jesus** — Geographic analysis
- **Jerome** — Infrastructure analysis

## Project Deliverables

- **Presentation:** `Team Tam Slam Slides.pdf`
- **Project synopsis:** `Team Tam Slam_Project Synopsis.pdf`
- **Analysis:** Python and Jupyter notebooks organized by research category

## Limitations

Our dataset includes recorded traffic accidents rather than all roadway travel. As a result, our findings should not be interpreted as causal relationships or as estimates of accident risk under specific conditions.

Additional considerations include missing data, sampling limitations, and differences in accident reporting.

---

**Team Tam Slam | Need4Data Datathon | Fall 2026**
