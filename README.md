# Violent Discipline Analysis Using UNICEF Data

This project analyzes the percentage of children experiencing violent discipline across various countries using UNICEF indicator data combined with metadata for enhanced insights. The analysis uses Python for data merging, cleaning, and visualizations, and the final output is rendered in a Quarto HTML report.

## Project Overview

The objective is to understand global patterns in child violent discipline, identify regions of concern, and support data-driven recommendations to promote child protection initiatives. The project processes real-world datasets, visualizes trends across countries, and simulates trends over time.

## Tools and Technologies

- Python (Pandas, Matplotlib, Plotnine, GeoPandas)
- Quarto (.qmd) for report generation
- Google Colab for development
- GitHub for project hosting

## Key Visualizations

- **World Map**  
  Displays a global heatmap where darker shades indicate higher percentages of children facing violent discipline.

- **Bar Chart**  
  Highlights the top countries with the highest percentages of violent discipline, providing a clear comparison across nations.

- **Scatter Plot**  
  Analyzes the relationship between GDP per capita and violent discipline, showing how economic factors may correlate with child protection outcomes.

- **Time-Series Plot**  
  Illustrates the trend of violent discipline over simulated years, helping observe overall increases or decreases.

## Structure

- `unicef_indicator_1.csv`: Cleaned dataset containing country-level observations.
- `unicef_metadata.csv`: Metadata with country attributes like region and income group.
- `AssignmentQutro.ipynb`: Colab notebook where data was processed and visualizations were built.
- `final_project.qmd`: Quarto file used to render the interactive report with code-folding enabled.

## Features

- ✅ Clean data merging with metadata  
- ✅ Visualizations with customized themes and titles  
- ✅ Foldable code blocks in the HTML report for readability  
- ✅ Simulated time series where missing historical data exists  

## How to Run

1. Clone the repository.
2. Open the notebook (`AssignmentQutro.ipynb`) in Google Colab.
3. Run all cells to generate outputs.
4. Render the final Quarto file (`.qmd`) into HTML using the command:  
   ```bash
   quarto render final_project.qmd
   ```

## Recommendations

- Strengthen global child protection policies in high-risk countries.
- Invest in community-based education programs to reduce violent discipline.
- Encourage more consistent data collection across all regions for monitoring.
- Promote international collaborations targeting childhood violence prevention.
- Link economic development programs with child welfare initiatives.
- Increase funding for intervention and awareness campaigns.
- Push for stricter enforcement of anti-violence laws globally.

## License

This project is for educational purposes only.
