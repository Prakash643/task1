# task1
#  Amazon Sales Dataset - Data Cleaning Project

This project focuses on cleaning and preprocessing an Amazon sales dataset that includes product details such as pricing, discounts, ratings, and listing dates.

---

##  Dataset Details

- **File Name**: `amazon_sales.csv`
- **Rows**: 100
- **Columns**: 8
- **Description**: Contains product-related information such as category, actual and discounted prices, discount percentage, rating, number of ratings, and the date the product was listed.

---

## Data Cleaning Tasks Performed


| 1️ Removed `₹` symbols and commas from `actual_price` and `discounted_price` |
| 2 Converted `discount_percentage` from string (e.g. "15%") to numeric (e.g. 15.0) |
| 3️ Converted `rating_count` from string with commas (e.g. "1,234") to integer |
| 4️ Converted `date_added` to `datetime` format (`dd-mm-yyyy`) |
| 5️ Standardized column names to lowercase and snake_case |
| 6️ Removed duplicate rows |
| 7️ Handled missing values in `rating` (filled with mean) |

---

##  Tools Used

- Python
- Pandas

---


---

##  Output

- **Cleaned File**: `amazon_sales_cleaned.csv`

---

##  Usage

You can use the cleaned dataset for:
- Exploratory Data Analysis (EDA)
- Visualization Projects
- Machine Learning Practice
- SQL or dashboard building

---

