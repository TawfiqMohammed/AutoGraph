# AutoGraph
## An Automated Exploratory Data Analysis (EDA) & Visualization Tool

AutoGraph is a robust tool for automating Exploratory Data Analysis (EDA) and generating visual insights from datasets, making data preparation seamless and insightful. This project was designed to help data analysts, data scientists, and business professionals streamline the EDA process and simplify complex data visualizations.

Live Demo: https://autographst.streamlit.app/

## Home Page
![Screenshot 2024-10-26 151813](https://github.com/user-attachments/assets/914446d9-0354-45f2-ae4d-ad977f329d81)

This project demonstrates:

- Automated EDA and customizable visualizations for quick, interactive insights
- Options for handling missing data, scaling numerical features, and transforming categorical columns
- An interactive interface built with Streamlit for easy file upload and feature selection
- Real-time updates on data preprocessing steps

## Key Features:

- Customizable EDA: Automatically generate insights, handle missing data, and transform columns with ease.
- Data Preprocessing: A suite of preprocessing options to clean and prepare data efficiently.
- Visualization Options: Choose from multiple visualization types to best represent your data.
- Data Restoration: Revert to the original dataset with a single click, ensuring flexibility.

## Installation and Setup:

Get started quickly by following these steps:
1. Clone the repository:
```bash
git clone https://github.com/TawfiqMohammed/AutoGraph.git
cd AutoGraph
```

2. Install dependencies: Ensure you have Streamlit and other required packages installed.
```bash
pip install -r requirements.txt
```
3. Launch AutoGraph:
```bash
streamlit run main.py
```

## Usage Guide
1. Upload a CSV file: Upload your dataset or select the example Titanic dataset from the sidebar.
    
2. Explore EDA: 

    - View Statistics: Generate and display summary statistics for your dataset, including count, mean, min, max, and standard deviation.

    - Visualize Distributions: Create histograms, box plots, and density plots to analyze the distribution of numerical features.

    - Analyze Relationships: Use scatter plots and correlation heatmaps to explore relationships between variables.

    - Categorical Analysis: Generate count plots to examine the distribution of categorical variables.

3. Preprocessing Dataset:

    - Handle Missing Data: Remove rows with missing data or fill missing values in numerical columns (using mean, median, or mode).

    - Transform Columns: Normalize numerical features and encode categorical variables.

    - Restore Data: Revert to the original dataset if needed.

4. Export & Share: Download your cleaned dataset and visualizations for further use.

## Find a bug?

If you found an issue or would like to submit an improvement to this project, please submit an issue using the issues tab above. If you would like to submit a PR with a fix, reference the issue you created!

## Known issues (Work in progress)

- Some visualization types may be limited by data types in the dataset (e.g., categorical vs. numerical).

- Future updates will include enhanced data transformation options and additional chart types.

## Enjoying This Project?
If you find AutoGraph useful, here’s how to support it:
 - Share Your Experience: Let us know how you're using it.
 - Contribute Ideas: Check the issues section for suggestions.
 - Provide Feedback: Your insights help improve the project.


