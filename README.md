# COVID-19 Data Analysis Project

Welcome to my COVID-19 Data Analysis Project repository! This project provides insights into the COVID-19 situation in India, with a focus on key statistics and trends. I have used two datasets: "Covid_19_india" and "Covid_vaccine_statewise" to perform the analysis.

## Project Overview

In this project, we aim to analyze the COVID-19 data in India. Here's an overview of the steps and analyses performed:

1. **Data Preprocessing**
   - We cleaned the "Covid_19_india" dataset by dropping unnecessary columns and adding an "Active Cases" column calculated from "Confirmed," "Cured," and "Death" columns.
   - We created a pivot table to summarize the data, providing a clearer view of the statistics.
   - We calculated the "Recovery Rate" and "Mortality Rate" to better understand the impact of the virus.

2. **Top 10 States**
   - We used the Seaborn package to create visualizations for the "Top 10 States with Active Cases" and the "Top 10 States with Death Rate." These visuals offer a quick snapshot of the most affected areas.

3. **Growth Trends**
   - We plotted the growth trends for the top 5 affected states, helping us understand the progression of the virus in these regions.

4. **Vaccination Data**
   - In the "Covid_vaccine_statewise" dataset, we renamed columns and dropped those with high null values.
   - We created a pie chart to compare male and female vaccination rates.
   - We cleaned the "State" column, removing the mention of "India."

5. **Most Vaccinated State**
   - We created a bar plot to identify the state with the highest vaccination rate, providing valuable insights into the vaccination efforts.

## Data Sources

- [Covid_19_india Dataset](https://github.com/abhisarahuja/Covid-19-Data-Analysis-Project-Using-Python-And-Tableau/blob/main/covid_19_india.csv)
- [Covid_vaccine_statewise Dataset](https://github.com/abhisarahuja/Covid-19-Data-Analysis-Project-Using-Python-And-Tableau/blob/main/covid_vaccine_statewise.csv)

## Getting Started

To replicate this analysis or explore the data further, you can find the Jupyter Notebook and the datasets in this repository.

## Dependencies

- Python
- Jupyter Notebook
- Pandas
- Seaborn
- Matplotlib

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

I would like to acknowledge the creators of the datasets and the open-source community for their valuable contributions to data analysis.

Feel free to explore the code, reproduce the analysis, or contribute to the project. If you have any questions or suggestions, please don't hesitate to reach out!

Happy Data Analysis!
