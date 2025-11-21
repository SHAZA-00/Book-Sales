# 📚 Book Sales Data Analysis

This project explores a **comprehensive dataset of book sales**, including publishing information, author details, ratings, genres, sales figures, and more.
Using Python and essential data-analysis libraries, the project uncovers trends in publishing years, genre distributions, author performance, pricing effects, and units sold.

---

## 🚀 Project Overview

The goal of this analysis is to:

* Clean and prepare book sales data.
* Explore relationships between:

  * Book ratings and rating counts
  * Sale price and units sold
  * Genre and rating distribution
  * Author performance (ratings & sales)
* Visualize important trends in the publishing industry.
* Produce business insights that could help publishers, retailers, and analysts.

---

## 📂 Dataset Description

The dataset includes **987 unique books** and the following key features:

| Column              | Description                     |
| ------------------- | ------------------------------- |
| Publishing Year     | Year the book was published     |
| Book Name           | Title of the book               |
| Author              | Book author(s)                  |
| language_code       | Language the book is written in |
| Author_Rating       | Rating category for the author  |
| Book_average_rating | Average reader rating           |
| Book_ratings_count  | Total number of ratings         |
| genre               | Fiction/Genre Category          |
| gross sales         | Total sales revenue             |
| publisher revenue   | Revenue retained by publisher   |
| sale price          | Book sale price                 |
| sales rank          | Ranking based on sales          |
| Publisher           | Publishing company              |
| units sold          | Units of the book sold          |

---

## 🧹 Data Cleaning Steps

* Removed books published before **1900**.
* Dropped missing values for `"Book Name"`.
* Removed duplicates.
* Checked column uniqueness and structure.
* Removed rows with missing critical data.
* Fixed inconsistent column names.

---

## 📊 Visualizations & Insights

### ✔ Publishing Year Distribution

Histogram showing publishing trends across decades.

### ✔ Genre Popularity

Bar chart showing counts of each genre category.

### ✔ Average Rating per Author

Ranked authors based on average reader ratings.

### ✔ Price vs Units Sold

Scatter plot showing how pricing influences demand.

### ✔ Language Distribution

Pie chart showing languages used in published books.

### ✔ Book Rating Count by Genre

Boxplot highlighting rating activity across genres.

### ✔ Total Sales per Author

Sum of gross sales grouped by author.

### ✔ Units Sold by Publishing Year

Time-series line chart for units sold over the years.

---

## 🛠 Technologies Used

* **Python**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Google Colab**

---

## 📁 Project Structure

```
📦 book-sales-analysis
│
├── Books_Data_Clean.csv
├── book_sales_analysis.ipynb
├── README.md   ← (You are here)
```

---

## 📈 Key Findings

* Most books in the dataset were published **after 1980**, with a strong concentration in the 2000s.
* **Genre fiction** dominates the dataset.
* Authors like **Bill Watterson, J.R.R. Tolkien, and George R.R. Martin** have some of the highest average ratings.
* Higher sale prices generally correlate with **fewer units sold**, as expected.
* English (eng / en-US) overwhelmingly dominates the language distribution.
* Certain publishing years show spikes in units sold, indicating market trends.

---

## 📬 Contact

If you’d like help improving your data analysis workflow or expanding this project, feel free to reach out!

---
