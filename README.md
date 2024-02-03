# xG Analysis Visualization

This Python script aims to visualize Expected Goals (xG) data from a CSV file. The script utilizes pandas for data manipulation, matplotlib for plotting, and Google Colab for uploading files. It generates step graphs representing cumulative xG values over time for home and away teams.


## Code Overview

- The script imports necessary packages: `pandas`, `matplotlib`, and `google.colab`.
- It reads the uploaded CSV file into a pandas DataFrame.
- Lists for home and away xG values and minutes are initialized.
- The script extracts team names from the DataFrame.
- Cumulative xG values are calculated using a custom function.
- Total xG values are determined.
- A plot is generated using matplotlib, displaying cumulative xG values over minutes for both home and away teams.

## Acknowledgments

This script was developed as part of an xG analysis tutorial.
