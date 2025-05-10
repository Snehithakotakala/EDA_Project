# 📊 Flipkart TV Market Insights: Web Scraping & EDA Project

This project presents a detailed analysis of the Flipkart TV market by using **web scraping** and **exploratory data analysis (EDA)** to uncover trends in pricing, brand popularity, screen size preferences, and customer ratings.

---

## 🧠 Objective

To understand consumer preferences in the TV market by analyzing:
- Best-selling TV brands
- Price segments
- Key product features (screen size, resolution, smart features)
- Customer feedback (ratings and reviews)

---

## 🔧 Technologies & Libraries Used

- **Python**
- **Web Scraping**: `BeautifulSoup`, `requests`, `re` (Regular Expressions)
- **Data Manipulation**: `Pandas`, `NumPy`
- **Data Visualization**: `Matplotlib`, `Seaborn`

---

## 🌐 Web Scraping Details

- **Source**: [Flipkart TV Listings](https://www.flipkart.com/search?q=tv)
- **Data Extracted**: Product name, brand, price, rating, reviews, resolution, screen size, and features.
- **Total Records Scraped**: 408 rows × 9 columns (raw data)

---

## 🧼 Data Cleaning Steps

- Handling missing values and duplicates
- Standardizing inconsistent formats
- Correcting data types
- Extracting structured info from text

---

## 📈 Exploratory Data Analysis

### 🔹 Univariate Analysis
- Frequency distribution of brands and screen sizes
- Most popular screen size: **32 inches**
- Most common brand: **InnoQ**

### 🔹 Bivariate Analysis
- Relationship between brand and resolution
- HD Ready is the most common resolution
- Higher screen size = slightly better ratings

### 🔹 Multivariate Analysis
- Correlation between price, ratings, reviews
- Price & screen size: moderate positive correlation
- Ratings don’t always increase with price

---

## 💡 Key Insights

- TVs priced ₹20,000–₹60,000 are most preferred.
- Full HD and HD Ready TVs show similar satisfaction levels.
- QLED TVs have slightly higher ratings but cost more.
- Mid-sized LED TVs offer the best value.
- Customer ratings positively correlate with the number of reviews.

---

## ❓ Business Questions Answered

1. Which brands are most popular?
2. What price range is most preferred?
3. How do screen size and resolution impact pricing?
4. Do higher-rated TVs cost more?
5. What features influence customer choices?
6. How does launch year affect pricing and demand?

---

## 🚧 Challenges Faced

- Handling dynamic web elements and CAPTCHAs
- Rotating user agents and proxies to avoid IP blocking
- Cleaning inconsistent text-based product data

---

## 🧾 Conclusion

This project highlights how data science can be used to generate business insights from e-commerce product listings. The results can help Flipkart (or similar platforms) with inventory planning and customer-centric marketing.



