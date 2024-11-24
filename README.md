# Restaurant Dataset Analysis  

![Screenshot 2024-11-24 184229](https://github.com/user-attachments/assets/e684c8dd-34b0-4962-a3da-78b97c890237)


## Overview  
This repository contains an in-depth analysis of a restaurant dataset comprising 17,304 rows and 22 columns. The dataset provides insights into various restaurant attributes such as location, cuisine types, pricing, ratings, and customer reviews. The primary goal of this analysis is to identify key trends, relationships, and anomalies to better understand the restaurant industry dynamics.

---

## Dataset Summary  
- **Number of Rows**: 17,304  
- **Number of Columns**: 22  
- **Dataset Size**: 2.9 MB  

### Data Types  
- **Numeric Columns**: 7 (e.g., *Average Cost for Two*, *Votes*, *Price Range*)  
- **Categorical Columns**: 15 (e.g., *City*, *Cuisines*, *Rating Text*)  

---

## Key Findings  

### 1. Restaurant Information  
- **Unique Restaurant Names**: 6,604  
  - *Cafe Coffee Day* is the most frequent, appearing 166 times.  
- **City Representation**:  
  - 43 cities covered, with *New Delhi* dominating (63% of entries, 10,946 rows).  

### 2. Cuisine Analysis  
- **Unique Cuisines**: 1,392  
  - *North Indian* is the most popular, appearing 1,872 times.  

### 3. Pricing and Costs  
- **Average Cost for Two**:  
  - Range: ₹0 - ₹8,000  
  - Mean: ₹623 | Median: ₹450  
- **Price Range**:  
  - Categorized into 4 levels: *Economical* to *Expensive*.  
  - Majority of restaurants fall under Level 1 (Economical).  

### 4. Ratings and Reviews  
- **Aggregate Rating**:  
  - Range: 0 - 4.9  
  - Mean: 2.52  
  - Most common ratings: 3.5-4.2 (*Good* and *Very Good*).  
- **Votes**:  
  - Range: 0 - 10,934  
  - Average Votes per restaurant: 137  

### 5. Missing Data  
- No missing values found across any columns.  

---

## Key Observations  
1. **City Representation**:  
   - *New Delhi* contributes to 63% of the entries.  
2. **Table Booking and Online Delivery**:  
   - Only 13% offer table booking.  
   - 28% offer online delivery.  
3. **Currency**:  
   - All pricing is in Indian Rupees (₹).  

---

## Relationships and Correlations  
- **Cost vs. Rating**:  
  - Higher-cost restaurants (*Price Range 3 & 4*) generally have higher ratings.  
- **Votes vs. Rating**:  
  - A positive correlation exists; more votes typically indicate better ratings.  
- **City vs. Cuisine**:  
  - Certain cuisines are region-specific (e.g., *Rajasthani* in Jaipur).  

---

## Common Orders  
The most frequently ordered items include:  
- Dal Makhani  
- Biryani  
- Rajma Chawal  
- Assorted Platters  

---

## Outliers and Anomalies  
- Restaurants with zero *Average Cost for Two* could indicate data entry errors.  
- Extremely high votes (above 10,000) may signify exceptional popularity or promotional activities.  

---

## Recommendations for Further Analysis  
1. **Clustering by Cuisine**:  
   - Identify cuisine preferences across cities to highlight regional trends.  
2. **Cost vs. Popularity**:  
   - Explore how pricing affects customer votes and ratings.  
3. **Customer Behavior**:  
   - Analyze relationships between delivery availability and aggregate ratings.  

---

## Getting Started  

### Prerequisites  
Ensure you have Python installed along with the following libraries:  
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  

### Installation  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/your-username/restaurant-dataset-analysis.git  
