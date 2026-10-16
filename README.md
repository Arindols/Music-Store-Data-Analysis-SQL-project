# 🎵 Music Store Data Analysis

## 🚀 Project Overview
This project leverages structured query language (SQL) to analyze a digital music store's relational database, extracting actionable insights to drive business growth. The database contains diverse, interconnected records covering inventory, customer demographics, sales history, and employee hierarchy. By systematically querying this data, the project uncovers purchasing trends, identifies high-value customer segments, and provides data-driven recommendations to optimize marketing and operational strategies.

## 🎯 Business Objectives
* 📦 **Inventory & Sales Optimization:** Identify top-selling genres, artists, and tracks to align digital inventory with actual market demand.
* 👥 **Customer Segmentation & Behavior:** Map purchasing patterns to pinpoint top-spending customers and high-performing geographic regions.
* 📢 **Strategic Marketing:** Pinpoint the most profitable cities and countries to optimize resource allocation for targeted promotional events.
* 🔍 **Advanced Trend Analysis:** Correlate customer spending habits with specific artist popularity and genre preferences to drive personalized recommendations.

## 🗄️ Database Schema
The analysis is performed on a normalized relational database consisting of the following key tables:
* 🎸 **Core Inventory:** `Artists` (artist details), `Albums` (discography), `Tracks` (individual song details, length, and media type).
* 🏷️ **Categorization:** `Genres` (music styles), `Media Types` (audio/video formats), `Playlists` (curated track collections).
* 💰 **Sales & Revenue:** `Invoices` (transaction headers), `Invoice Lines` (granular purchase details).
* 🏢 **Stakeholders:** `Customers` (demographics and purchase history), `Employees` (organizational hierarchy and support roles).

## ❓ Key Business Questions Addressed
### 🧑‍💼 Employee & Customer Profiling
* 🥇 Who is the senior-most employee based on job title and hierarchy?
* 💎 Who are the most valuable customers based on lifetime spending?
* 🌍 Who are the top-spending customers within each specific country?

### 🗺️ Geographic & Revenue Insights
* 📈 Which countries generate the highest volume of invoices?
* 💵 What are the top three individual invoice totals across the dataset?
* 🏙️ Which city generates the most revenue, making it the ideal location for a sponsored promotional event?

### 🎧 Music Trends & Preferences
* 🤘 Which customers are the primary consumers of Rock music?
* 🎤 Who are the top-performing Rock artists based on listener purchases?
* ⏱️ Which tracks exceed the average song length across the entire catalog?
* 💸 How much revenue has each customer contributed to specific artists?
* 💿 What is the single most popular music genre in every country?

## 🛠️ Tools & Technologies
* 💻 **SQL:** Advanced querying techniques including `JOIN` operations, `GROUP BY` aggregations, Common Table Expressions (`WITH`), and Window Functions for ranking and running totals.
* 📊 **Relational Database Management:** Systematic data extraction and relationship mapping across a multi-table schema.

## 📈 Key Insights & Results
* ✅ **Smarter Inventory Management:** Streamlined focus on high-performing tracks and dominant genres to maximize catalog relevance.
* 🎯 **Targeted Customer Engagement:** Provided actionable geographic data to focus marketing campaigns and promotional events in regions with proven high ROI.
* 🚀 **Driven Sales Growth:** Established a clear framework for identifying top customers, allowing for targeted loyalty initiatives and a deeper understanding of spending behaviors.

## 🔮 Future Scope
* 📈 **Business Intelligence Integration:** Connect the database to BI tools (such as Power BI or Tableau) to automate dashboard reporting and visualize real-time insights.
* 🧠 **Advanced Analytics:** Expand the database schema with additional engagement metrics (e.g., listening time, skip rates) for deeper cohort analysis.
* 🤖 **Machine Learning Deployment:** Utilize historical purchase data to train predictive recommendation engines and model future customer churn.
