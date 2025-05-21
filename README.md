# SQL-DWH-PROJECT
This is my SQL Data Warehouse project, to be honest, this project is not really mine, I repeated the video tutorial by Bara Khatib Salkini (respect), but to be fair, I'll say that I wrote everything myself without neural networks!

🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers: Data Architecture

    Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
    Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
    Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.


