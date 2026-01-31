# Zomato Data Analysis Using Python

A comprehensive data analysis project exploring restaurant data from Zomato to uncover insights about restaurant ratings, costs, online ordering trends, and dining preferences.

## 📋 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Analysis Workflow](#analysis-workflow)
- [Key Insights](#key-insights)
- [Visualizations](#visualizations)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

This project performs exploratory data analysis (EDA) on Zomato restaurant data to understand various aspects of the restaurant industry including customer preferences, pricing patterns, and service availability. The analysis provides valuable insights for restaurant owners, food enthusiasts, and business analysts.

## 📊 Dataset

The dataset (`Zomato-data-.csv`) contains the following features:

- **name**: Restaurant name
- **online_order**: Whether online ordering is available (Yes/No)
- **book_table**: Table booking availability (Yes/No)
- **rate**: Restaurant rating (out of 5)
- **votes**: Number of votes received
- **approx_cost(for two people)**: Approximate cost for two people
- **listed_in(type)**: Type of restaurant (Buffet, Cafes, Dining, etc.)

**Dataset Size**: 150 restaurants

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization

## 💻 Installation

### Prerequisites
Make sure you have Python 3.x installed on your system.

### Setup Instructions

1. Clone this repository:
```bash
git clone https://github.com/Vivekk-007/zomato-data-analyst
cd zomato-data-analysis
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook Zomato_Data_Analysis_Using_Python.ipynb
```

## 🔍 Analysis Workflow

### 1. Data Loading and Exploration
- Import necessary libraries
- Load the Zomato dataset
- Display initial data overview

### 2. Data Cleaning and Preprocessing
- Handle rating format (convert from '4.1/5' to 4.1)
- Check for missing values
- Verify data types and structure

### 3. Exploratory Data Analysis

The analysis covers the following aspects:

#### Restaurant Type Distribution
- Count plot showing distribution of restaurant types
- Total votes by restaurant type

#### Rating Analysis
- Distribution of ratings across all restaurants
- Rating comparison between online and offline ordering restaurants
- Box plot analysis of ratings by online order availability

#### Online Ordering Trends
- Count of restaurants offering online ordering
- Relationship between online ordering and ratings

#### Cost Analysis
- Distribution of approximate costs for two people
- Cost patterns across different restaurant types

#### Top Performers
- Identification of restaurants with maximum votes
- Popular restaurant categories

#### Correlation Analysis
- Heatmap showing relationship between restaurant type and online ordering availability

## 📈 Key Insights

Based on the analysis, the project reveals:

1. **Online Ordering Impact**: Analysis of how online ordering affects restaurant ratings and popularity
2. **Restaurant Type Preferences**: Distribution and popularity of different restaurant categories
3. **Pricing Patterns**: Cost variations across different restaurant types
4. **Rating Distribution**: Overall quality distribution of restaurants in the dataset
5. **Vote Leaders**: Most popular restaurants based on customer engagement

## 📊 Visualizations

The project includes the following visualizations:

- **Count Plots**: Restaurant type distribution, online ordering availability
- **Line Plots**: Votes by restaurant type
- **Histograms**: Rating distribution
- **Box Plots**: Rating comparison by online order availability
- **Heatmaps**: Restaurant type vs online ordering availability
- **Bar Charts**: Cost distribution patterns

## 📁 Project Structure

```
zomato-data-analysis/
│
├── Zomato_Data_Analysis_Using_Python.ipynb    # Main Jupyter notebook
├── Zomato-data-.csv                            # Dataset
├── README.md                                    # Project documentation             
```

## 🚀 Usage

1. Open the Jupyter notebook:
```bash
jupyter notebook Zomato_Data_Analysis_Using_Python.ipynb
```

2. Run all cells sequentially to reproduce the analysis

3. Modify parameters or add new analysis as needed

4. The notebook is organized in logical sections for easy navigation

## 🔮 Future Enhancements

Potential improvements for this project:

- [ ] Add more advanced statistical analysis
- [ ] Implement machine learning models to predict ratings
- [ ] Include location-based analysis
- [ ] Add cuisine type analysis
- [ ] Create an interactive dashboard using Plotly or Dash
- [ ] Perform sentiment analysis on reviews (if available)
- [ ] Compare multiple cities or regions
- [ ] Add time-series analysis if temporal data is available

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

Your Name
- GitHub: [@Vivekk-007](https://github.com/Vivekk-007/zomato-data-analyst)
- LinkedIn: [vivekk](https://www.linkedin.com/in/vivek-kumar-63587a384/)

## 🙏 Acknowledgments

- Dataset source: Zomato
- Inspiration: Understanding food industry trends through data
- Special thanks to the Python data science community

---

**Note**: This is an educational project for learning data analysis and visualization techniques. The insights are based on the provided dataset and may not represent current market conditions.

## 📞 Contact

For questions or feedback, please open an issue in the repository or contact at kumarvivek05093896@gmail.com

---

⭐ If you found this project helpful, please consider giving it a star!
