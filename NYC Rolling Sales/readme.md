# 🏢 NYC Building Data Analysis

In this project, I analyzed New York City building data to uncover insights on building prices, characteristics, and classifications across the city. This project involved extensive data cleaning, handling outliers, and performing exploratory data analysis (EDA) to gain valuable insights.

## 🧹 Data Cleaning and Preprocessing
1. **Data Cleaning**: 
   - Removed unnecessary columns, handled null values, and adjusted data types where necessary.
   
2. **Outlier Detection and Removal**:
   - **Price Column**: Detected significant outliers, with some building prices exceeding **$5 billion**, and removed these values to enable better visualization and analysis.
     - Outliers account for about **20%** of the data, with:
       - **11,000 buildings** priced under **$10,000** (impractical values).
       - **1,100 buildings** priced over **$5 million**.
   - **Total Units**: Some buildings had over **200-2,000 units**, which are outliers in this dataset. Removed instances where total units exceeded **20**, as these values represented a small fraction of data (only 80 values).
   - **Land Square Feet**: Removed outliers:
     - **70 instances** with values over **20,000 sq ft**, as they distorted distribution.
     - **7,348 instances** with values under **600 sq ft** or equal to **0**.

## 📊 Exploratory Data Analysis (EDA)

<details>
<summary>Click to expand for EDA insights</summary>

### 🏢 Building Age and Pricing Trends
- Buildings constructed between **1920-1940** appear to be more expensive on average than newer buildings.

### 🏙️ Building Distribution by Borough
- Most buildings in the dataset are located in **Queens** and **Brooklyn**.

### 🏷️ Tax Class and Pricing
- **Tax Class Distribution**: 
  - **Class 1** is the most common tax classification, followed by **Class 2**.
  - Average prices:
    - **Class 4**: ~**$2.2 million** (higher end, often pricier buildings).
    - **Class 1**: ~**$0.7 million**.

### 🏠 Average Prices by Building Class
- **Rental Walk-Up Apartments**: Average price is **$1.6 million**.
- **Condos with Elevators**: Average price is **$1.1 million**.

### 🏢 Most Common Building Class Categories
| Building Class Category              | Count   |
|--------------------------------------|---------|
| 01 ONE FAMILY DWELLINGS              | 12,358  |
| 02 TWO FAMILY DWELLINGS              | 9,528   |

### 🏙️ Average Prices by Borough
| Borough         | Average Price (USD) | Count   |
|-----------------|---------------------|---------|
| Manhattan       | 2,382,055.46        | 287     |
| Brooklyn        | 1,096,351.70        | 8,120   |
| Queens          | 728,421.63          | 10,458  |
| Bronx           | 586,003.67          | 3,314   |
| Staten Island   | 532,137.30          | 4
