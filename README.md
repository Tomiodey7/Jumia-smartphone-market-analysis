# Jumia Nigeria Smartphone Market Analysis

> From web scraping to business insights: How is Nigeria's E-commerce smartphone market priced?

![Dashboard Preview]<img width="6150" height="3525" alt="Jumia Market Analysis Dashboard" src="https://github.com/user-attachments/assets/a6b9f2b7-4e87-4e30-9dcd-a723f0e35476" />


### 🔍 Project Overview
Scraped 133 smartphone listings from Jumia.com.ng to analyze pricing strategy, brand positioning and affordability in Nigeria's largest e-commerce market.

**Key Findings:**
- **₦65K to ₦1.47M** - Massive 22x price gap serving both entry-level and premium buyers
- **₦289K Average Price** - Mid-range (120k-300k) dominates with 72 models (54% of market)
- **16 Brands Battleground** - Samsung leads volume (48 listings) while Apple leads price (₦888K avg)
- **70% under ₦500k** - Market is skewed to affordable, not ultra-budget

### 🛠️ Tech Stack
- **Scraping:** Python (Requests, BeautifulSoup, Pandas) - Jumia.com.ng
- **Cleaning:** Python (Regex for price parsing, deduplication)
- **Analysis:** Pandas (133 products, 16 brands, 4 price segments)
- **Visualization:** Power BI (KPI cards, Brand analysis, Price segmentation)

### 📊 Dashboard Features
- 4 KPI Cards: Total Products, Avg/Min/Max Price with custom orange icons
- Average Price by Brand - Premium vs Budget positioning
- Count by Brand - Market share by listings
- Price Segments - Budget <120k, Mid 120-300k, Upper Mid 300-600k, Premium >600k
- Interactive Filters: Brand & Price Segment

### 📁 Files
- `jumia_smartphone_scrapping.ipyng` - Web scraping script
- `JUMIA_Smartphones.csv` - Cleaned dataset (133 rows)
- `JUMIA SMARTPHONE MARKET ANALYSIS.pbix` - Power BI file
- `Jumia Market Analysis Dashboard.jpg` - Dashboard image

### 💡 Business Impact
For retailers: Stock more mid-range (120k-300k) - that's where demand is.
For brands: Differentiation is on specs (RAM/Storage/Camera), not just price.

---
Data Source: Jumia.com.ng | Date: Oct 2026
