# Healthcare Provider Analysis

A team-based healthcare data project exploring provider specialties, geographic coverage, professional experience, and patient ratings through web scraping, data cleaning, and exploratory analysis.

## Project Overview

Healthcare provider listings contain information that can help describe the availability and characteristics of providers. However, missing values, multiple practice locations, and differences in patient review counts can make comparisons difficult.

This project collects and analyzes provider profile data to investigate these patterns and communicate findings through a Jupyter notebook and presentation.

## Objectives

- Examine the distribution of providers across specialties and locations.
- Assess missing values and other data quality issues.
- Explore relationships between provider experience and patient ratings.
- Compare rating patterns within selected specialties.
- Investigate practice location counts and geographic coverage.
- Consider patient feedback counts when interpreting ratings.

## Project Workflow

1. Collect healthcare provider profile data.
2. Combine collected files into a consolidated dataset.
3. Inspect and prepare the data for analysis.
4. Perform exploratory and multivariate analysis.
5. Present findings, limitations, and recommendations.

The main notebook contains the project's code, analysis, visualizations, and explanations.

## Repository Contents

| Folder | Contents |
| --- | --- |
| `notebooks/` | Main project notebook |
| `data/` | A 100-row dataset sample and full dataset access instructions |
| `presentation/` | Final team presentation |
| `report/` | HTML export of the project notebook |

## Dataset

The repository includes a 100-row sample to demonstrate the dataset's structure.

The project's analysis and reported results use the full dataset. The sample alone will not reproduce those results.

See [dataset documentation](data/README.md) for full dataset access and setup instructions.

## My Contribution

**Ashish Rao Soorneni — Team Manager and Multivariate Analysis**

- Coordinated team work and supported the integration of project contributions.
- Analyzed relationships among provider experience, specialty, practice location count, and patient ratings.
- Examined experience and rating patterns within selected specialties.
- Compared results across minimum patient feedback thresholds.
- Contributed to project insights, recommendations, and presentation preparation.

This repository presents a collaborative Team 07 project. The complete analysis includes contributions from multiple team members.

## How to Explore the Project

- Open `notebooks/` to review the code and analysis.
- Download the HTML file from `report/` and open it in a browser to view the exported notebook.
- Open `presentation/` for the team's presentation.

## Running the Notebook

1. Download or clone this repository.
2. Follow the instructions in `data/README.md` to obtain the full dataset.
3. Open the main notebook in Jupyter Notebook or VS Code.
4. Install the Python packages imported by the notebook.
5. Update file paths to match your local dataset locations.
6. Review the scraping cells before execution. Use the existing dataset when you only want to reproduce the analysis.
7. Run the required analysis cells in order.

## Interpretation and Limitations

- Provider listings reflect the source website and collection period.
- Missing or invalid values can affect comparisons.
- Ratings should be interpreted alongside patient feedback counts and specialty.
- Search locations and provider practice addresses may differ.
- Observed relationships do not establish causation.
- Patient ratings alone do not establish clinical quality.

## Acknowledgments

Developed by Team 07 as an academic midterm project at the University of Houston.
