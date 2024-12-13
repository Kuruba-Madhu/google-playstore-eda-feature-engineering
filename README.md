# Google Play Store EDA and Feature Engineering

## Problem Statement
Today, 1.85 million apps are available for users to download, with 2.56 million apps specifically on the Google Play Store. These apps significantly influence our daily lives. This project aims to explore and analyze the dataset to uncover insights such as:
- The most popular app category.
- The app with the largest number of installs.
- The app with the largest size, among other metrics.

## Dataset Information
- **Rows:** 10,841
- **Columns:** 20

The dataset was collected from the Google Play Store and contains information about app categories, ratings, reviews, installs, and other app-related attributes.

---

## Steps Followed

### Step 1: Data Loading
- Loaded the dataset into the Jupyter Notebook for analysis.

### Step 2: Data Profiling and Cleaning
- Checked the dataset for missing values and inconsistencies.
- Removed null entries in critical columns such as `Installs`, `Size`, and `Category` to ensure accurate analysis.

### Step 3: Data Transformation
- Processed the `Size` column to handle non-standardized units (e.g., MB, KB).
- Cleaned and converted `Installs` into numerical format for analysis.
- Extracted relevant features such as price tier, content rating, and app type.

### Step 4: Exploratory Data Analysis (EDA)
- Visualized the distribution of app categories, ratings, and installs.
- Identified the most popular app categories by total installs.
- Analyzed app size distribution and its correlation with installs and ratings.

### Step 5: Insights Generation
- Found the app with the highest installs.
- Discovered trends in app sizes and ratings across categories.
- Determined seasonal and categorical preferences for apps.

### Step 6: Feature Engineering
- Created new features like `Size_Tier` (Small, Medium, Large) for better grouping.
- Generated `Revenue_Estimate` by combining `Price` and `Installs`.

---

## Key Insights

### [1] Category Insights:
- **Most Popular Category:** `Games`
- **Least Popular Category:** `Beauty`

### [2] App-Specific Insights:
- **App with Most Installs:** `Facebook` (1 Billion+ installs).
- **Largest App by Size:** `Adobe Acrobat Reader` (200MB).

### [3] Size vs. Installs:
- Small-sized apps (< 50MB) generally have higher installs compared to larger apps.

### [4] Rating Distribution:
- Apps with a rating above 4.0 are predominantly from the `Education` and `Health & Fitness` categories.

### [5] Content Rating:
- Most apps are rated as `Everyone`, indicating broad accessibility.

---

## Visualizations
- **Bar Charts:** Popular categories and installs distribution.
- **Scatter Plots:** Correlation between app size and installs.
- **Box Plots:** Rating distribution across app categories.
- **Heatmaps:** Relationships between price, installs, and rating.

---

## Future Enhancements
- Perform sentiment analysis on user reviews to gain deeper insights into user satisfaction.
- Introduce machine learning models to predict app popularity based on features.
- Include time-series analysis to track app trends over time.

---






