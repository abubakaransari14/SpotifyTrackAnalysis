# 🌍 World Population Web Scraping & Analysis

This project demonstrates how to scrape, clean, analyze, and visualize global population data using Python.

The data is collected from **World Population Review** and transformed into a structured dataset for analysis.

---

# 📊 Project Overview

The goal of this project is to practice:

- Web Scraping
- Data Cleaning
- Data Analysis
- Data Visualization

The script extracts country population statistics from a website and performs exploratory data analysis using Python.

---

# 🛠 Technologies Used

- Python
- BeautifulSoup
- Requests
- Pandas
- Matplotlib
- Plotly

---

# 📥 Data Collection

The dataset is scraped from:

https://worldpopulationreview.com/countries

The script:

1. Sends an HTTP request to the webpage
2. Parses the HTML using BeautifulSoup
3. Extracts the population table
4. Converts the table into a Pandas DataFrame

---

# 🧹 Data Cleaning

Several preprocessing steps were performed:

- Removed commas from numeric values
- Removed percentage signs
- Converted strings to numeric data types
- Cleaned special characters from area values
- Created a custom function to convert units like:
  - `M → Million`
  - `K → Thousand`

---

# 📈 Analysis Performed

The project includes the following analysis:

- Total world population
- Total number of countries
- Top 10 countries by population
- Top 10 countries by land area
- Countries with highest population growth
- Countries with lowest population growth

---

# 📊 Visualizations

The project generates several visualizations:

### Top 10 Countries by Population
Interactive bar chart showing the most populated countries.

### Population Growth Rate Comparison
Horizontal bar chart comparing growth rates.

### Population vs Area Scatter Plot
Scatter plot showing relationships between:

- Population
- Country Area
- Population Density
- Growth Rate

Log scales are used for better visualization of large value ranges.

---

# 📂 Project Structure

```

web-scraping-population/
│
├── webScraping.ipynb
├── README.md
└── world_population.xlsx 

```

---

# 🚀 How to Run

1. Clone the repository

```
git clone https://github.com/yourusername/world-population-analysis.git
```

2. Install dependencies

```
pip install pandas requests beautifulsoup4 plotly matplotlib
```

3. Run the notebook

```
jupyter notebook
```

---

# 🎯 Learning Outcomes

Through this project I practiced:

- Extracting data from websites
- Handling messy real-world data
- Using Pandas for data analysis
- Creating interactive visualizations
- Building an end-to-end data workflow

---

# 📬 Feedback

If you have suggestions or improvements, feel free to open an issue or contribute!

---

⭐ If you like the project, consider giving the repository a star.
