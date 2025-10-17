# 💰 Bangkok Airbnb Market Analysis & Dynamic Pricing Framework
This project aims to analyze active **Airbnb listings in Bangkok** from 2012 to 2022 to develop a data-driven pricing framework for hosts by analyzing key market dynamics that influence prices.

## Business Question
"What are the key factors that influence Airbnb prices in Bangkok? How can these insights help hosts develop a more **competitive pricing framework** to maximize revenue?

## Objectives
1. Identify pricing patterns across neighborhoods, room types, and host characteristics
2. Examine how availability, reviews, and listing, experience affect listing price
3. Compare how the different market segments (normal, luxury, and long-term) are positioned and how hosts can align with them.
4. Provide data-driven pricing guidelines for new and existing Airbnb hosts.

## Case Study
### Stakeholders
1. Individual Airbnb Hosts, we can deliver revenue increase through price optimization.
2. Airbnb Strategy team: Bangkok market insight can be used to optimize pricing suggestions and improve customer-facing operations.

### Positioning
I will be positioning myself as a Pricing/Revenue Analyst conducting market study for Bangkok's Airbnb ecosystem.

## Data Dictionary
Listing data only consists of Active listings from 2012 to 2022.

| feature | description | 
|---|---|
| id | Listing unique ID. |
| name | Listing name. |
| host_id | Host unique ID. |
| host_name | Host name. |
| neighborhood | Listing neighborhood location. |
| latitude | Geographic coordinate. |
| longitude | Geographic coordinate. |
| room_type | Entire home/apt, Hotel room, Private room, Shared room. |
| price | Daily renting price in THB. |
| minimum_nights | Minimum number of nights to rent of the listing. |
| number_of_reviews | Amount of reviews the listing has. |
| last_review | Date of the latest review. |
| calculated_host_listings_count | Amount of listing this specific host has. |
| availability_365 | How many days the listing is available in a year. |
| number_of_reviews_ltm | Amount of reviews the listing has in the last 12 months. |

## Data Collection and Cleaning
- Original and cleaned + segmented data is available in this repository.
- Full cleaning process notebook provided in this repository.

## Tools & Libraries Used

- **Python:** `pandas`, `numpy`, `matplotlib`, `seaborn`  
- **Visualization:** Tableau (for geographic heatmaps & dashboards)  
- **Data Source:** InsideAirbnb.com (Bangkok listings dataset)  
- **Other:** GeoPandas (for spatial validation), scikit-learn (optional regression testing)

---

## 💡 Key Insights

- **Location matters most:** District proximity to business or tourist hubs strongly influences price.  
- **Professional hosts** dominate the luxury segment and maintain higher average prices.  
- **Short-term stays** are the core of the Bangkok Airbnb market; long minimum nights reduce visibility and customer base.  
- **Guest engagement** (reviews) is not directly tied to price — suggesting guests prioritize affordability.  
- **Luxury segment** operates under a different logic: fewer listings but much higher price ceilings.

