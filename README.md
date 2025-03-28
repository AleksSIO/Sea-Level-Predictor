# 🌊 Sea Level Predictor

This project is part of the [freeCodeCamp Data Analysis with Python](https://www.freecodecamp.org/learn/data-analysis-with-python/) curriculum. It uses historical sea level data to visualize trends and make predictions of future sea level rise through 2050.

## 📂 Project Structure

. ├── sea_level_predictor.py # Script containing the plotting logic ├── main.py # Development entrypoint to test your function ├── test_module.py # Unit tests for validation ├── epa-sea-level.csv # Sea level dataset from 1880 to 2014 └── sea_level_plot.png # Output image of your final visualization

## 📊 Features

- Loads sea level data from 1880–2014.
- Creates a **scatter plot** of historical sea level rise.
- Fits and plots a **regression line** using all data (1880–2014) to predict rise through 2050.
- Fits and plots a **second regression line** using data from **2000 onward** to compare recent trends.
- Labels axes and sets an appropriate title.

## 🧪 Technologies Used

- **Python 3**
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [SciPy](https://scipy.org/)

## 🚀 How to Run the Project

1. Make sure you have the required dependencies installed:

```bash
pip install pandas matplotlib scipy```
Run the project locally:

```bash
python main.py```
The script will:

Generate a plot image and save it as sea_level_plot.png

Run unit tests defined in test_module.py

📈 Output Plot Description
The resulting plot will:

Show a scatter of sea level data from 1880 to 2014.

Display:

A red regression line for the full dataset (1880–2014) projecting to 2050.

A green regression line for the data from 2000 onward projecting to 2050.

Include:

X-axis label: Year

Y-axis label: Sea Level (inches)

Title: Rise in Sea Level

📚 Dataset Source
Global Average Absolute Sea Level Change, 1880–2014
U.S. Environmental Protection Agency (EPA)
Using data from CSIRO (2015) and NOAA (2015)
