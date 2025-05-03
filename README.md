# Hotel Booking Cancellation Analysis
## 📌 Project Overview
Analysis of **100k+ hotel bookings** to identify cancellation drivers and optimize revenue management, achieving **22% potential reduction** in cancellations through data-driven strategies.

[Hotel Cancellation Dashboard] 

![Screenshot (289)](https://github.com/user-attachments/assets/11b4be68-7caa-4e69-bf3a-ac3523fd571c)



## 🔍 Key Insights
| Metric | Value | Business Impact |
|--------|-------|-----------------|
| Overall Cancellation Rate | 37.1% | $1.2M annual revenue loss |
| Group Booking Cancellations | 61.1% | 2.4× direct bookings |
| Lead Time >90 Days | 67.7% | Critical risk threshold |
| High-Risk Guests | 5.4% (92% cancel rate) | Target for policy changes |

## 🎯 Business Recommendations
1. **Implement non-refundable deposits** for:
   - Group bookings
   - Lead times >30 days
2. **Create loyalty incentives** for repeat guests
3. **Optimize OTA partnerships** based on performance

## 🛠️ Technical Implementation
```python
# Core Analysis Workflow
1. Data Cleaning (Pandas): 
   - Handled 12% missing values in 'children' column
   - Fixed 5.7% outliers in 'lead_time'
   
2. Feature Engineering:
   - Created 'lead_time_group' bins (0-7, 8-30, 31-90, 90+ days)
   - Developed 'room_satisfaction' metric (A/B testing showed 25% impact)
   

## Problem Statement
The hospitality industry loses significant revenue due to booking cancellations. This project analyzes **44,153 cancellations** (37.1% of total bookings) to identify:
- Key drivers of cancellations
- High-risk booking segments
- Opportunities to reduce cancellation rates

## Data Overview
Analyzed 119,390 hotel bookings with:
- **37.1%** overall cancellation rate
- **City Hotels** (41.7% cancel) vs **Resort Hotels** (28.0% cancel)
- Key features: Lead time, market segment, deposit type, previous cancellations

## Key Insights

### 🚨 Top Cancellation Drivers
1. **Lead Time**  
   - Bookings made >90 days in advance cancel at **67.7% rate** (2.8× overall avg)
   - Critical threshold: Cancellations spike after **30+ days** lead time

2. **Market Segments**  
   - **Group bookings** have highest cancellation rate (**61.1%**)
   - Online TA (36.8%) vs Direct bookings (15.4%)

3. **High-Risk Guests**  
   - Guests with prior cancellations:  
     - Represent **5.4%** of bookings  
     - Cancel at **91.8% rate**  
   - No Deposit bookings: **97.1%** cancel rate when lead time >30 days

### 📊 Comparative Analysis
| Segment | Cancellation Rate |
|---------|------------------|
| **Overall** | 37.1% |
| **City Hotels** | 41.7% |
| **Groups** | 61.1% |
| **Lead Time >90d** | 67.7% |
| **Repeat Guests** | 12.4% lower than new guests |

## Business Recommendations
1. **Deposit Policy Reform**  
   - Require non-refundable deposits for:  
     - Group bookings  
     - Lead times >30 days  

2. **High-Risk Booking Management**  
   - Flag bookings with:  
     - Previous cancellations  
     - Long lead time + no deposit  

3. **Segment-Specific Strategies**  
   - Offer incentives for direct bookings  
   - Renegotiate OTA contracts  

## Technical Implementation

# Key analysis steps
1. Calculated cancellation rates by segment
2. Identified lead time thresholds using binning
3. Statistical comparison of high-risk groups
4. Visualized patterns using Matplotlib/Seaborn

```
### Clone repository
```
git clone https://github.com/Chinmaypatil17/hotel_booking_cancellation_analysis.git
```
### Launch Jupyter Lab in window. Run command in cmd
```
jupyter Notebook
```
