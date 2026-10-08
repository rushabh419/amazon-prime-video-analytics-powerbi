### 1. Project Title
* Title: Amazon Prime Video Catalog & Content Analytics Dashboard
* Repository Name: amazon-prime-video-analytics-powerbi

### 2. Short Description
* An interactive business intelligence project developed in Microsoft Power BI analyzing the Amazon Prime Video catalog.
* Evaluates content volume across genres, maturity ratings, release timelines, and global production hubs using a custom-styled dark theme.

### 3. Purpose
* Analyze Catalog Composition: Measure the distribution between feature movies and episodic TV series.
* Track Content Acquisition Trends: Identify release year patterns and historical content scaling over time.
* Map Regional & Genre Distribution: Pinpoint top-producing countries and dominant genre categories across the platform.
* Apply Advanced BI Design: Build a production-grade dashboard with custom branding, conditional formatting, geographic mapping, and scorecard KPIs.

### 4. Tech Stack
* Visualization & BI: Microsoft Power BI Desktop
* Data Transformation (ETL): Power Query
* Analytics & Modeling: DAX / Distinct Aggregations
* Data Storage / Source: CSV

### 5. Example Walkthrough
* Use Case: Evaluating geographic content distribution and rating density.
* Action: Review the filled map and genre bar charts.
* Observed Insight: The United States (250+ titles) and India (~230 titles) represent the largest content bases, with movies significantly outnumbering TV shows and additions spiking rapidly post-2015.
* Conclusion: Demonstrates strategic expansion in high-growth streaming markets alongside traditional Hollywood releases.

### 6. Data Source
* Dataset: Amazon Prime Video Movies and TV Shows Dataset (Kaggle)
* Format: .csv
* Key Attributes:
  * show_id: Unique record identifier
  * type: Content type (Movie or TV Show)
  * title: Title of the content
  * director: Director name(s)
  * cast: Lead actors and cast
  * country: Country of production/distribution
  * date_added: Platform addition date
  * release_year: Original release year
  * rating: Age and maturity classification
  * duration: Duration in minutes or number of seasons
  * listed_in: Genre and category classifications
  * description: Content summary

### 7. Features & Highlights
* Executive KPI Cards: 6 scorecard tiles showing Total Titles, Total Ratings, Total Genres, Unique Directors, Start Year, and End Year.
* Choropleth Filled Map: Global distribution map with conditional gradient fills displaying title volume by nation.
* Donut Chart Split: Proportional breakdown comparing Movies vs. TV Shows.
* Release Trend Area Chart: Multi-line historical area chart plotting releases across years by content type.
* Ranked Horizontal Bar Charts: Comparative visual breakdown of top genres and age ratings.
* Branded Dashboard UI: Custom dark theme layout utilizing Amazon Prime color codes (#19222D background, #00A8E1 accents) with rounded border styling.

### 8. Business Impact & Insights
* Film-Centric Catalog: Movies represent the vast majority of assets, highlighting an acquisition model historically oriented toward standalone films over high-retention episodic content.
* Regional Focus Markets: High concentration in the US and India indicates targeted regional subscriber acquisition strategies.
* Library Modernization: Exponential catalog growth post-2015 reveals aggressive content licensing to compete with competing streaming platforms.
* Strategic Recommendations: Identifies opportunities to increase episodic series acquisition to improve user retention and rebalance under-represented genres.
