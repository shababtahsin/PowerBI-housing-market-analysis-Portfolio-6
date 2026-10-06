# 🏠 Austin Housing Data Insights
### Power BI Business Analysis Project

## 📌 Project Overview

This project analyses **15,171 residential properties** across the Austin, Texas housing market using **Power BI**.

The objective was to create an interactive Business Intelligence solution that helps users understand how residential property values vary according to:

- Geographic location
- Property type
- Living area
- Lot size
- Bedrooms and bathrooms
- Property features
- School characteristics
- Housing amenities

The report allows users to move from a high-level market overview into detailed geographic, school, feature, and individual-property analysis.

The project demonstrates practical Business Analyst and Data Analyst skills including:

- Business problem definition
- Data modelling
- DAX
- Interactive reporting
- Field parameters
- Key Influencers
- Geographic analysis
- Market segmentation
- Business insight generation

---

# 🖥️ Power BI Report

## Cover Page

![Austin Housing Cover Page](images/00.cover-page.png)

The report opens with a navigation page that introduces the analytical areas available within the dashboard:

- Summary View
- Location View
- School View
- Feature View

This provides users with a guided entry point into the report.

---

# 🎯 Business Problem

Residential property values across Austin vary substantially between locations, property types, housing characteristics, neighbourhoods, and available amenities.

Headline property price alone does not explain these differences.

The business therefore requires an analytical solution capable of answering:

- Where are higher- and lower-priced properties concentrated?
- Which housing types dominate the market?
- Which property characteristics are associated with different price levels?
- How do school characteristics vary across neighbourhoods?
- Which amenities are more common in higher-priced properties?
- Which factors appear to influence listing price?
- How can users dynamically investigate individual market segments?

---

# 🎯 Project Objectives

1. Provide an executive overview of the Austin housing market.
2. Analyse housing availability across different property types.
3. Compare median and average housing prices.
4. Identify geographic concentrations of residential properties.
5. Analyse school characteristics across Austin neighbourhoods.
6. Compare property prices across different housing features.
7. Identify characteristics associated with higher listing prices.
8. Enable interactive filtering and market segmentation.
9. Provide detailed property-level information.
10. Translate housing data into business-oriented insights.

---

# 📊 Dataset Overview

| Metric | Result |
|---|---:|
| Total Properties | **15,171** |
| Median Property Price | **$405,000** |
| Average Property Price | **$512,768** |
| Median Living Area | **1,975 sq ft** |
| Average Living Area | **2.21K sq ft** |
| Median Lot Size | **8,276 sq ft** |
| Average Lot Size | **119K sq ft** |
| Maximum Property Price | **$13.5M** |

The dataset contains information covering:

- Property price
- Home type
- City
- ZIP code
- Street address
- Latitude and longitude
- Bedrooms
- Bathrooms
- Living area
- Lot size
- Garage spaces
- Parking features
- Number of stories
- Year built
- Cooling
- Heating
- Spa
- View
- Homeowners association
- Appliances
- School ratings
- School size
- Student-to-teacher metrics

---

# 🛠️ Tools & Techniques

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Data Modelling**
- **Field Parameters**
- **Interactive Slicers**
- **Dynamic Visuals**
- **Geographic Mapping**
- **Key Influencers**
- **Tooltips**
- **Bookmarks / Navigation**
- **Business Intelligence**
- **Market Segmentation**
- **Business Analysis**

---

# 📊 1. Executive Summary

![Summary Dashboard](images/01.summary-dashboard.png)

The Summary page provides an executive-level overview of the Austin housing market.

### Core KPIs

- **15,171 properties**
- **$405K median property price**
- **$512.8K average property price**
- **1,975 sq ft median living area**
- **8,276 sq ft median lot size**

The page also analyses:

- Properties by home type
- Properties by ZIP code
- Properties by construction year
- Median vs average property price
- Property feature availability

---

## 🏡 Housing Type Distribution

Single-family properties dominate the dataset.

| Property Type | Property Count |
|---|---:|
| Single Family | **14,241** |
| Condo | **470** |
| Townhouse | **174** |
| Multiple Occupancy | **96** |
| Vacant Land | **83** |

Approximately **94% of analysed properties are Single Family homes**.

### Business Insight

The dataset predominantly represents the Austin single-family housing market.

Analysis of smaller property categories should therefore be interpreted with greater caution because their sample sizes are considerably lower.

---

# 💰 Median vs Average Property Price

The dashboard shows:

- **Median Property Price:** ~$405K
- **Average Property Price:** ~$513K

The average is substantially higher than the median.

### Business Insight

The housing-price distribution is positively skewed by higher-value properties.

For describing a typical Austin property, the **median is therefore more representative than the average alone**.

---

# 🗺️ 2. Location Analysis

![Location Analysis](images/02.location-analysis.png)

The Location page provides an interactive geographic view of residential properties across the Austin area.

Users can select a price range and observe where matching properties are geographically concentrated.

The analysis uses:

- Latitude
- Longitude
- Property price
- Geographic filtering
- Dynamic price ranges

### Business Purpose

This allows users to identify:

- Premium residential areas
- Lower-price housing areas
- Geographic property clusters
- Properties within selected price ranges
- Spatial differences across the Austin housing market

### Business Insight

Austin should not be treated as one homogeneous housing market.

Property values vary materially by geography, making location one of the most important dimensions when comparing residential properties.

---

# 🎓 3. School Analysis

![School Analysis](images/03.school-analysis.png)

The School page evaluates education-related characteristics surrounding residential properties.

### School KPIs

| Metric | Result |
|---|---:|
| Average School Rating | **5.85** |
| Average School Size | **1.24K** |
| Median Students per Teacher | **14.80** |
| Average Primary Schools | **0.91** |
| Average Middle Schools | **1.08** |
| Average High Schools | **0.94** |
| Average High School Size | **1.335K** |

The page analyses:

- School rating
- School size
- Students per teacher
- ZIP code
- Geographic school distribution

Properties can be grouped into categories such as:

- Poor
- Average
- Good
- Exceptional

### Business Insight

School characteristics vary considerably across Austin neighbourhoods and provide an additional dimension for understanding residential-market segmentation.

Any relationship between school characteristics and housing price should be interpreted as **association rather than causation**.

---

# 🔥 4. Property Features Analysis

![Property Features Analysis](images/04.features-analysis.png)

The Features page investigates how median home price changes across different property characteristics.

A dynamic parameter allows users to switch between variables such as:

- Garage spaces
- Bedrooms
- Bathrooms
- Parking features
- Number of parking features
- Number of stories
- Appliances
- Home type

### Business Purpose

Instead of creating a separate chart for every property characteristic, the field parameter allows several business questions to be answered through a single dynamic visual.

---

# 🧠 Key Influencers Analysis

The report also includes Power BI's **Key Influencers** visual.

This investigates factors associated with increases in listing price.

Variables considered include:

- Living area
- Lot size
- Bedrooms
- Bathrooms
- Garage spaces
- Parking
- Stories
- Appliances
- Year built
- Other property features

### Business Insight

Residential property value is multi-dimensional.

No single feature fully explains property price.

A meaningful property assessment should consider:

**Location + Property Size + Property Configuration + Amenities + Neighbourhood Characteristics**

---

# 🏊 Property Amenities and Price

Selected features show different median price levels.

Examples include:

| Property Feature | Without | With |
|---|---:|---:|
| Garage | ~$385K | **~$425K** |
| View | ~$395K | **~$475K** |
| Spa | ~$399K | **~$575K** |

### Business Interpretation

Properties with garages, views, and spas tend to occupy higher-price market segments.

However, these differences should not be interpreted as the direct monetary value created by the feature itself.

Other characteristics such as property size, location, construction quality, and land value may contribute simultaneously.

---

# 🔍 5. Interactive Filter Panel

![Interactive Filter Panel](images/05.filter-panel.png)

The report contains a detailed filter panel allowing users to conduct self-service analysis.

Users can filter by:

### Property Configuration

- Bedrooms
- Bathrooms
- Parking features
- Number of parking features
- Garage spaces
- Number of stories
- Appliances

### Property Features

- HOA
- Cooling
- Heating
- Spa
- View
- Home type

### Location

- City
- ZIP code
- Street address

### School Characteristics

- School rating
- School size
- Classroom size

### Numeric Ranges

- Listing price
- Living area
- Year built
- Lot size

### Business Value

This allows stakeholders to investigate highly specific property segments without requiring a separate report for every question.

For example:

> 3-bedroom single-family properties with garages, selected school ratings, a specific ZIP code, recent construction years, and a defined listing-price range.

---

# 🏠 6. Property-Level Tooltip

![Property Tooltip](images/09.Property%20Tooltip.png)

The report includes a dedicated property tooltip page designed to provide more detailed information about individual properties.

The tooltip contains:

- Address
- City
- ZIP code
- Listing price
- Living area
- Lot size
- Bedrooms
- Bathrooms
- Home type
- Parking spaces
- Garage spaces
- Number of stories
- Appliances
- Accessibility features
- Community features
- Patio and porch features
- Window features
- Waterfront features

### Business Value

The tooltip allows the user to move from market-level analysis to **individual property inspection** without leaving the report.

This improves the report's usefulness for:

- Property comparison
- Buyer research
- Real-estate screening
- Detailed listing investigation

---

# 🗃️ 7. Data Model

![Power BI Data Model](images/06.data-model-main.png)

The solution uses a structured analytical model instead of relying on one flat table.

The main model contains:

- `housing_fact`
- `house`
- `location`
- `schools`
- `features`
- `features_pivot`
- `description`
- `word_summary_pqe`
- `_measures`

### Model Design

The central `housing_fact` table connects to supporting analytical tables containing:

- House characteristics
- Location information
- School information
- Feature information
- Property descriptions

This structure supports filtering and interaction across multiple report pages.

---

# ⚙️ 8. Parameters & Supporting Tables

![Power BI Parameter Tables](images/07.data%20model%202.png)

The model also includes disconnected parameter and helper tables used for interactive report behaviour.

Examples include:

- Parameter range tables
- Field parameters
- School-group parameters
- Ranking tables
- Measure support tables

These support:

- Dynamic metric selection
- Dynamic visual axes
- School segmentation
- Range filtering
- Ranking
- Interactive report behaviour

### Business Intelligence Value

The use of disconnected parameter tables reduces the need for duplicated visuals and allows the same dashboard components to answer multiple analytical questions.

---

# 💡 Key Business Findings

## 1. Austin Housing Prices Are Highly Segmented

The substantial difference between median and average housing prices indicates the presence of a premium housing segment.

---

## 2. Single-Family Housing Dominates the Dataset

Approximately **94%** of analysed properties are Single Family homes.

---

## 3. Geographic Location Is Critical

Property prices vary significantly across Austin.

Comparing properties at city-wide level alone can therefore hide important geographic differences.

---

## 4. Property Size and Configuration Matter

Living area, lot size, bedrooms, bathrooms, garages, and other structural characteristics are associated with different housing-price segments.

---

## 5. School Characteristics Add Neighbourhood Context

School ratings, school size, and student-to-teacher measures provide an additional dimension for evaluating neighbourhoods.

---

## 6. Premium Amenities Are Associated With Higher Prices

Properties containing garages, spas, and views generally show higher median prices than properties without these features.

---

## 7. Property Value Is Multi-Dimensional

No single variable fully explains residential property price.

Housing value should therefore be analysed using multiple dimensions simultaneously.

---

# 💼 Business Recommendations

## 1. Prioritise Median Price for Benchmarking

Because premium properties increase the average significantly, median property price provides a more representative measure of typical market value.

---

## 2. Compare Properties Within Similar Locations

Properties should be compared within relevant geographic areas or ZIP codes rather than across Austin as a whole.

---

## 3. Compare Similar Property Types

Single-family properties, condominiums, townhouses, and other housing types should be analysed within their respective market segments.

---

## 4. Evaluate Multiple Property Characteristics

Property assessment should incorporate:

- Location
- Living area
- Lot size
- Bedrooms
- Bathrooms
- Home type
- Property features
- School characteristics

---

## 5. Treat Amenity Premiums Carefully

Higher median prices among homes with garages, spas, or views indicate association rather than direct causal value.

---

## 6. Use Interactive Segmentation for Stakeholder Analysis

The report's dynamic filters and field parameters enable users to investigate very specific housing-market segments.

This supports:

- Buyer property searches
- Investor screening
- Market comparisons
- Neighbourhood analysis
- Property positioning
- Real-estate research

---

# ⚠️ Analytical Limitations

## Property-Type Imbalance

Approximately 94% of observations are Single Family homes.

Other property types have much smaller sample sizes.

---

## Association Does Not Equal Causation

Relationships between listing price and characteristics such as:

- School rating
- Garage availability
- Spa
- View
- Living area

represent observed associations.

They do not prove independent causal effects.

---

## Confounding Variables

Location, property size, land value, property quality, amenities, and neighbourhood characteristics may influence housing prices simultaneously.

---

## Outliers

The dataset contains unusually high-priced and unusually large properties.

These observations may materially influence averages.

Median measures are therefore used extensively throughout the analysis.

---

# 📌 Executive Conclusion

The Austin residential property market demonstrates substantial variation across geography, property structure, school characteristics, and housing amenities.

The typical property in the dataset has a median price of approximately **$405K**, while the higher average price of approximately **$513K** reflects the influence of premium properties.

Single-family housing represents approximately **94% of analysed properties**, making it the dominant residential segment.

The analysis demonstrates that housing valuation should be approached as a **multi-dimensional business problem** rather than relying on listing price alone.

The final Power BI solution allows stakeholders to move from:

**Executive Overview → Geographic Analysis → School Analysis → Property Features → Detailed Property Inspection**

within a single interactive analytical environment.

---

# 📁 Repository Structure

```text
Austin-Housing-Data-Insights/
│
├── README.md
├── housing_data_project.pbix
├── austinHousingData.xlsx
│
└── images/
    ├── 00.cover-page.png
    ├── 01.summary-dashboard.png
    ├── 02.location-analysis.png
    ├── 03.school-analysis.png
    ├── 04.features-analysis.png
    ├── 05.filter-panel.png
    ├── 06.data-model-main.png
    ├── 07.data model 2.png
    └── 09.Property Tooltip.png
