# 📺 Netflix Content Analysis Dashboard (Python + Power BI)

An interactive Power BI dashboard project analyzing global Netflix content data. The project uses Python for data preprocessing and Power BI for multi-page visualization of trends in movies and TV shows across genres, countries, and years.

---

## 📊 Dashboard Overview

The dashboard consists of **3 main pages**:

### 1. **Home Page**
- Overview of total shows, directors, genres, countries.
- Area chart of title count over years by type.
- Donut chart for content type distribution.
- Bar chart for top genres by number of shows.
- Filled map showing content spread by country.

### 2. **Movies Page**
- Filtered visuals focused only on movie content.
- KPIs: total movies, unique directors, release year range.
- Genre-wise and rating-wise movie distributions.

### 3. **TV Shows Page**
- Visuals focused on TV shows only.
- KPIs for total shows, regions, and years.
- Charts showing type, ratings, and trends for shows.

---

## ⚙️ Tools & Technologies Used

- **Python (Pandas, Jupyter Notebook)** – for data cleaning & preprocessing
- **Power BI** – for visualization and dashboard design
- **DAX** – for calculated fields and dynamic titles
- **CSV Dataset** – publicly available Netflix content data

---

## 🧹 Data Preprocessing

Before building the dashboard, the dataset was cleaned using Python:
- Removed duplicates and null values.
- Normalized `genre`, `cast`, and `country` columns.
- Extracted `Year`, `Month`, and `Day` from `date_added`.
- Created new fields for easier filtering (e.g., content type).

All transformations were done in **Jupyter Notebook** and the cleaned file was exported to Excel for Power BI modeling.

---


## 📌 Note

- This project is for **portfolio and learning purposes only**.
- The data is sourced from a publicly available Netflix dataset and is not affiliated with Netflix Inc.

---

## 👨‍💻 Author

**Tanmeet Singh Reel**  
- 📧 tanmeetsingh202@gmail.com  

---
