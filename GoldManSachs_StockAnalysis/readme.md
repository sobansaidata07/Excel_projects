# Goldman Sachs Stock Analysis (1999–2026) – README

---

## 1. Purpose
This analysis explores the historical stock performance of **Goldman Sachs** from 1999 to 2026. It is prepared **for educational purposes only** and is intended to demonstrate:

- Data cleaning and transformation  
- Trend analysis of stock prices, trading volume, and dividends  
- Use of Excel functions like **VLOOKUP** and **XLOOKUP**  

---

## 2. Data Source & Ownership
- The dataset was **downloaded from Kaggle** using Python without logging in.  
- **Original data ownership belongs to the uploader on Kaggle**, not the author.  
- Source: Kaggle dataset (publicly available)  
- Data includes:  
  - Date (daily timestamps)  
  - Open, High, Low, Close prices  
  - Trading volume  
  - Dividends  
  - Stock splits  

---

## 3. Data Cleaning Steps
1. **Date Formatting:** Converted timestamps to `MM/DD/YYYY` and added Year, Month, Quarter, Day Name, etc.  
2. **Lookup Functions:**  
   - `VLOOKUP` → to map Month Numbers to Month Names and Quarters  
   - `XLOOKUP` → to map Year to historical events or dividend info  
3. **Volume & Price Cleanup:** Converted volumes to millions for readability and checked dividend values.  
4. **Final Clean Dataset:** Ready for pivot tables, charts, and trend analysis.  

---

## 4. Important Notes
- This analysis is **for learning and demonstration only**.  
- No financial advice is given.  
- All insights and visualizations are based on **publicly available Kaggle data**.  
- The report focuses on trends, growth patterns, dividends, and trading volume insights.  

---

## 5. Recommended Usage
- Use this README alongside the **Word report** or **Excel dataset**.  
- Great for learning:  
  - Data cleaning techniques  
  - Stock market trend analysis  
  - Using Excel lookup functions effectively  

---

