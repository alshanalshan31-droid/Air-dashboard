# Global Airbnb Performance Dashboard

1 Short Description / Purpose

An interactive Power BI dashboard that analyses Airbnb's global performance across 10 major cities. It shows how the platform grew, matured, declined, reinvented itself and was hit by COVID-19, and compares cities on market share, guest ratings and pricing. The goal is to turn raw listing and review data into clear, decision-ready insights.

2 Tech Stack

- **Power BI Desktop**: data modelling and dashboard design
- **Power Query**: data cleaning and transformation
- **DAX**: measures and calculations (e.g. city rank, averages, counts)

3 Data Source

Dataset from [Maven Analytics](https://mavenanalytics.io/data-playground/airbnb-listings-reviews) (Airbnb data).

4 Features and Highlights

**KPI summary**
- 279.712K listings across 10 cities
- 182K unique hosts
- 144 property types
- 5.373M reviews

**Overview page: Airbnb lifecycle (2008-2020)**
- Area chart of total listings by room type (Private room, Shared room, Entire place, Hotel room)
- Timeline split into six phases: Introduction, Growth, Maturity, Decline, Reinvention and COVID-19
- Key takeaways: rapid rise led by entire places, a partial recovery that never regained the earlier peak, and a sharp COVID-19 collapse across every room type

**Reviews page**
- Market share by city, with Paris leading, followed by New York and Sydney
- City rank table
- Average rating matrix by city across Accuracy, Cleanliness, Communication, Location and Value, with colour-coded scores
- Average price by room type: Hotel room (~800), Entire place (~673), Shared room (~580), Private room (~462)

**Ratings page**
- Additional rating analysis

**Interactivity**
- Page navigation across Overview, Reviews and Ratings tabs
- Cross-filtering between visuals

## Dashboard Preview

![Overview](images/overview.png)
![Reviews](images/reviews.png)
