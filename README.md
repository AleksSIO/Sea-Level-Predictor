# 🌊 Sea Level Predictor

This project is part of the [freeCodeCamp Data Analysis with Python](https://www.freecodecamp.org/learn/data-analysis-with-python/) curriculum.  
It uses historical sea level data to visualize trends and predict future sea level rise through the year 2050.

---

## 📁 Project Structure

```
sea_level_predictor.py   # Script containing the plotting logic  
main.py                  # Development entrypoint to test your function  
test_module.py           # Unit tests for validation  
epa-sea-level.csv        # Sea level dataset from 1880 to 2014  
sea_level_plot.png       # Output image of your final visualization  
```

---

## 📊 Features

- Loads sea level data from 1880–2014  
- Creates a **scatter plot** of historical sea level rise  
- Fits and plots a **regression line** using all data (1880–2014) to predict rise through 2050  
- Fits and plots a **second regression line** using data from **2000 onward**  
- Proper axis labels and an informative title  

---

## 🧪 Technologies Used

- **Python 3**
- **Pandas**
- **Matplotlib**
- **SciPy**

---

## 🚀 How to Run the Project

1. Install the required libraries:

```bash
pip install pandas matplotlib scipy
```

2. Run the project:

```bash
python main.py
```

What it does:

- Generates a plot saved as `sea_level_plot.png`  
- Runs unit tests defined in `test_module.py`

---

## 📈 Output Plot Description

The plot will include:

- A scatter plot of actual sea level data (1880–2014)  
- A **red regression line** (full dataset) projected through 2050  
- A **green regression line** (from year 2000) projected through 2050  
- Labels:
  - **X-axis**: Year  
  - **Y-axis**: Sea Level (inches)  
  - **Title**: *Rise in Sea Level*

---

## 📚 Dataset Source

> Global Average Absolute Sea Level Change, 1880–2014  
> U.S. Environmental Protection Agency (EPA)  
> Data from CSIRO (2015) and NOAA (2015)
