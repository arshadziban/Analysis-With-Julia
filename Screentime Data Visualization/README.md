# App Usage Data Analysis

This project performs an in-depth analysis of app usage data using Julia. The data includes metrics such as usage time (in minutes), notifications received, times the app was opened, and the date of each usage entry. Various statistical and visualization techniques are used to gain insights from the data.

## Dataset

The dataset used in this project is from Kaggle:

- **Dataset**: [Mobile Apps Screentime Analysis](https://www.kaggle.com/datasets/anandshaw2001/mobile-apps-screentime-analysis)

You can download the dataset from Kaggle and use it to run the analysis script.

## Requirements

To run this project, you need to have the following Julia packages installed:

- CSV
- DataFrames
- Statistics
- Plots
- Dates

You can install them using the following commands:

```julia
using Pkg
Pkg.add("CSV")
Pkg.add("DataFrames")
Pkg.add("Statistics")
Pkg.add("Plots")
Pkg.add("Dates")
