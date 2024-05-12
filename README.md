# McDonald's Menu Nutritional Analysis

## Overview
This repository hosts a comprehensive analysis of McDonald's menu, focusing on the nutritional aspects of various food items offered. It provides insights into nutritional content, exploring how different categories compare in terms of health metrics.

### Repository Structure
- `data/`: Contains the `menu.csv` file with nutritional information about McDonald's menu items.
- `Scripts/`: Includes Python scripts and Jupyter Notebook used for detailed data analysis.
  - `Nutritional_facts_in_McDonald's_menu.ipynb`: Jupyter Notebook containing the analysis with visualizations.
  - `nutritional_facts_in_mcdonald's_menu.py`: Python script version of the Jupyter Notebook analysis.
- `Insight.docx`: A Word document summarizing key insights derived from the data.

## Key Insights
- **Item Categorization:** Coffee & Tea items dominate the menu, suggesting a focus or large variety in this category. Salads and Desserts are less prevalent.
- **Nutritional Content:** 
  - Breakfast items are rich in cholesterol, likely from eggs and meats.
  - Smoothies & Shakes are high in Vitamin C, aligning with their fruit content.
  - Salads contain high levels of Vitamin A, indicative of ingredients like leafy greens and carrots.
- **Nutrient Correlations:** 
  - Positive correlation between carbohydrates and sugars across the menu.
  - Notable correlation between total fat and cholesterol, particularly in breakfast items.

## Business Implications
These insights assist in strategic menu planning, highlighting potential health trends to target and optimizing the variety of offerings to align with customer preferences:
- **Menu Development:** Consider expanding less represented categories like Salads and Desserts.
- **Health Trends:** Focus on offering options with lower cholesterol and sugars to cater to health-conscious consumers.
- **Marketing Strategy:** Leverage popular categories in promotional activities to attract more customers.

## How to Use This Repository
1. **Data Analysis:**
   - Navigate to the `Scripts/` directory to view or run the Jupyter Notebook (`Nutritional_facts_in_McDonald's_menu.ipynb`) or the Python script (`nutritional_facts_in_mcdonald's_menu.py`).
2. **Insight Report:**
   - Read the `Insight.docx` document for a summary of the key findings and implications.

## Requirements
- Python 3.8+
- Jupyter Notebook
- Libraries: pandas, matplotlib, seaborn (Install via `pip install -r requirements.txt`)
