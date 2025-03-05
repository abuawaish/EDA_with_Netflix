# **Exploratory Data Analysis with Netflix Dataset**

This repository contains an exploratory data analysis (EDA) on a Netflix dataset. The analysis aims to uncover insights about Netflix content including show types, genres, release trends, ratings, and other relevant metrics to better understand patterns in streaming data.

## Dataset

The dataset used for this analysis typically includes details such as:
- **Title**: Name of the Netflix show or movie.
- **Director**: Director(s) of the content (if available).
- **Cast**: Main actors/actresses.
- **Country**: Country of origin.
- **Date Added**: When the content was added to Netflix.
- **Release Year**: The year the content was originally released.
- **Rating**: Age rating (e.g., PG, R, TV-MA).
- **Duration**: Length of the movie or number of seasons for a TV show.
- **Genre/Category**: The genre or type of content.
- **Description**: A brief overview of the content.

## Repository Structure

- **Netflix_EDA.ipynb**: Jupyter Notebook containing the full EDA workflow. This notebook walks through data cleaning, visualization, and insight generation.
- **data/**: Directory containing the Netflix dataset.
- **figures/**: Directory where the generated plots and visualizations are saved.
- **requirements.txt**: List of Python packages required to run the analysis.

## Analysis Overview

The EDA focuses on:
- **Genre Distribution**: Examining the breakdown of content across different genres.
- **Content Trends Over Time**: Analyzing how Netflix’s content has evolved over the years, including the rise of Netflix Originals.
- **Rating Insights**: Investigating the distribution of age ratings and how they correlate with other factors.
- **Duration Analysis**: Understanding the differences in runtime for movies versus the number of seasons for TV shows.
- **Geographical Patterns**: Looking at content based on country of origin and its impact on Netflix’s global appeal.

## How to Run the Analysis

1. **Clone the repository:**
   ```bash
   git clone https://github.com/abuawaish/EDA_with_Netflix.git
   ```
2. **Navigate into the directory:**
   ```bash
   cd EDA_with_Netflix
   ```
3. **Install the required libraries:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Launch the Jupyter Notebook:**
   ```bash
   jupyter notebook Netflix_EDA.ipynb
   ```

## Prerequisites

Make sure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Required Python libraries such as pandas, numpy, matplotlib, seaborn, and plotly

## Author

This project is maintained by [Abu Awaish](https://github.com/abuawaish).  
For any questions or suggestions, feel free to contact via email at abuawaish7@gmail.com.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- Appreciation to the open-source community for the libraries and tools that made this analysis possible.
- Special thanks to Netflix for providing a dataset that inspires such interesting data exploration.
