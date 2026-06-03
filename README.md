# NTFLX-DASBOARD
🎬 Netflix Content & Global Distribution Dashboard
📝 Short Description
An interactive Power BI dashboard that provides a comprehensive overview of Netflix's media catalog, tracking distribution trends across countries, release years, age ratings, and global production hubs. It translates streaming data into insights regarding content types, major regional contributors, and specific directors or cast members.

🛠️ Tech Stack
Business Intelligence Tool: Power BI Desktop — Used for layout design, geospatial configuration, and report canvas interactions.

Data Modeling & Expressions: DAX (Data Analysis Expressions) — Leveraged to create calculated metrics and aggregation plots (such as Sum of Release Year metrics).

Mapping Integration: Microsoft Bing Maps API — Built directly into the dashboard canvas for native global geographical tracking.

📂 Data Source & Schema
The data model simulates a comprehensive Netflix media catalog tracking global metadata across movies and television productions. Key attributes within the underlying schema include:

Content Identification: Unique records for movie or show Title, Director, and Cast members.

Fulfillment Details: Classification data including content Type (Movie or TV Show) alongside localized production information.
Centralized Dynamic Filter Sidebar: Features a dedicated, red-accented left navigation control panel equipped with five independent dropdown slicers for real-time slicing by Country, Director, Title, Cast, and content Type.

Dark Mode Brand-Aligned UX: Designed with a high-contrast dark theme incorporating Netflix's signature corporate crimson aesthetic and official logo asset.

Temporal & Classification Data: Chronological metrics for Release_Year along with corresponding maturity or runtime Rating benchmarks (e.g., G, 66 min, 74 min, 84 min, Classic Movies).

Geographical Mapping: Global coordinates paired with explicit fields for production Country origins (such as United States, India, United Kingdom, South Africa, Spain, among others).

✨ Features & Highlights
Global Geospatial Content Distribution: Features an integrated interactive world map visual (Country and type) that plots production data onto geographic coordinates to track distribution weight across international boundaries.

Regional Volume Distribution Bar Chart: Employs a bar chart plotting the "Sum of release_year by country", clearly establishing the United States and India as the largest historical volume contributors to the catalog.

Maturity & Duration Segmentation Pie Chart: Integrates a multi-slice pie chart ("Sum of release_year by rating") that evenly weights and visualizes content distribution according to distinct program runtimes, genres, and age ratings.

Detailed Catalog Matrix: A tabular data view in the upper-right corner that allows stakeholders to cross-reference production countries directly with specific directors (e.g., matching South Africa to Zuko Nodada, or India to Zoya Akhtar).
