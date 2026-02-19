# Elist-Retail-Analysis-Orders-to-Insights
## Project Overview
This analysis explores sales data from Elist, an electronics retailer offering premium electronics products. The goal of the project is to uncover sales trends, product performance insights, loyalty program effectiveness, and regional demand patterns to support data-driven business decisions.

## Table of Contents
### 1. Executive Summary ###
   Elist recorded $28.12M in total sales revenue from 2019 to 2022, with approximately 108K orders placed across product categories including laptops, audio devices, phones, and accessories. 
   Sales peaked at $1.25M in December 2020, likely driven by holiday demand, before gradually declining to a low of $0.18M in October 2022.
   ![Alt Text](https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/Overall%20Sales%20Trend%20Y19-22.png)

   Sales performance showed a clear concentration in high-value products. MacBook Air and ThinkPad laptops consistently contributed the majority of total revenue despite lower order volumes with only 6,880 combined orders, 
   their $1,381.05 average order value (AOV) far exceeded other categories, underscoring the outsized role premium products play in overall business performance.
   ![Alt Text](https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/Revenue%20v%20Orders%20v%20AOV.png)
   
   From a regional perspective, North America emerged as the dominant market, accounting for 51.78% of total revenue. In contrast, APAC and LATAM demonstrated comparatively lower demand and 
   higher variability in product performance, signaling opportunities for targeted regional strategies and deeper market penetration.
   ![Alt Text](https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/Regional%20Metrics.png)

   Membership Growth (top bars):
   Loyalty member growth started very low at 1.83% in 2019, surged to a peak of 19.14% in 2021, then eased back to 11.31% in 2022. Non-loyalty growth followed a similar arc but peaked earlier in 2020 at 19.28%, then steadily declined    to 9.97% by 2022. This suggests the loyalty program gained strong momentum through 2021 but may be maturing or slowing in its ability to attract new members.
   
   AOV % (bottom lines):
   Loyalty members showed steady AOV growth from $207 in 2019 to $245 in 2022, while non-loyalty customers were more volatile, peaking at $345 in 2020 before declining to $214 in 2022. 
   Notably, 2022 marks the first year loyalty members outspent non-loyalty customers, suggesting the program is beginning to drive stronger purchasing behavior, though there remains room to further incentivize 
   higher spend among members.
   ![Alt Text](https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/Loyalty%20Memebership%20Growth.png)

   Overall, the analysis highlights Elist’s reliance on premium products for revenue growth, the strong performance of the North American market, and clear opportunities to enhance loyalty program effectiveness and 
   regional sales strategies.

### 2. Insights Deep Dive ###
#### 1. Sales Trends Analysis ####


| Insight Area | Key Observation | Business Interpretation |
|------|-------------|-------------|
| YoY Growth | 2020 shows strong YoY growth across most months, while 2022 shows consistent YoY decline | Indicates post-pandemic peak in 2020 followed by demand normalization in 2022 |
| Seasonality | Sales peak during Aug–Dec across multiple years | Q3–Q4 are critical revenue-driving periods |
| Volatility | Large MoM fluctuations observed, especially in 2021 | Reflects external shocks and recovery cycles impacting revenue |


| Metrics Trend Sales Revenue  | Sales Revenue YoY |
|------------------|------------|
| <img src="https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/Metrics%20Trend%20sales%20revenue.png" width="580"> | <img src="https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/YoY%20of%20Sales%20Revenue.png" width="320"> |
| | 🟦 Positive Growth · 🟧 Negative Growth |




#### Key Insights ####

2020 represents the strongest revenue year, driven by sustained YoY growth across most months.

2022 shows significant YoY contraction, especially in the second half of the year, signaling demand slowdown.

Sales exhibit clear seasonality, with consistent uplift during Q3–Q4, making these months critical for planning. 

#### 2. Orders Analysis ####

| Insight Area | Key Observation | Business Interpretation |
|------|-------------|-------------|
| YoY Growth Pattern | Strong YoY growth in 2020 and 2021 across most months, followed by sharp declines in 2022 | Demand surged during recovery years and weakened significantly in 2022 |
| Seasonality | Orders consistently peak during Q3–Q4 | Seasonal demand and campaigns strongly influence order volume |
| Volatility | 2022 shows steep negative YoY values (especially Sep–Dec) | Indicates customer demand contraction rather than short-term fluctuation |



| Metrics Trend Orders | Orders YoY |
|------------------|------------|
| <img src="https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/Metrics%20Trends%20orders.png" width="550"> | <img src="https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/YoY%20of%20Orders.png" width="350"> |
| | 🟦 Positive Growth · 🟧 Negative Growth |


#### Key Insights ####

Order volumes experienced strong YoY expansion in 2020–2021, reflecting increased customer acquisition and demand.

A sharp YoY decline in 2022 suggests a slowdown in customer purchasing behavior rather than operational issues.

Seasonal spikes in Q3–Q4 remain consistent, highlighting the importance of demand planning during peak months.

#### 3. Average Order Value (AOV) ####

  
| Insight Area | Key Observation | Business Interpretation |
|------|-------------|-------------|
| YoY Stability | AOV remains relatively stable compared to orders and sales | Revenue volatility is driven more by volume than basket size |
| 2021 Decline | Majority of 2021 months show negative YoY AOV | Increased discounting or shift toward lower-priced products |
| 2022 Recovery | AOV decline moderates in 2022 with some positive YoY months | Pricing strategy or product mix improvement |



| Metrics Trend AOV  | AOV YoY |
|------------------|------------|
| <img src="https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/Metrics%20Trends%20AOV.png" width="550"> | <img src="https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/YoY%20of%20AOV.png" width="350"> |
| | 🟦 Positive Growth · 🟧 Negative Growth |



#### Key Insights ####

AOV in 2020 surged across all months (peak: +43.65% YoY in 
August), suggesting pandemic demand drove both volume and 
higher-value purchases simultaneously confirming 2020 
growth was broad-based rather than volume-driven alone.

AOV declined sharply through 2021, with every month recording 
negative YoY figures, bottoming at -22.36% in December
indicating customers shifted toward lower-value purchases as 
pandemic demand normalized.

2022 showed partial stabilization, with September returning 
to modest positive YoY growth (+3.55%), though overall AOV 
remained under pressure suggesting pricing strategy or 
product mix adjustments may be needed to restore pre-pandemic 
spending levels.


      
### 2. Product Performance Analysis ###
#### 2.1 Sales Revenue by Year and Products
| Insight Area | Key Observation | Business Interpretation |
|------|-------------|-------------|
| Top Performer  | 27in 4K Gaming Monitor peaked in 2021 at $3.35M.|Unlike most products peaking in 2020, sustained demand continued into 2021.|
| Strong Contributors | MacBook Air peaked in 2020 at $3.09M, AirPods consistent across 2020–2021 | Premium laptops and audio drove majority of revenue during peak years |
| Consistent Decline | All top products show revenue decline in 2022 | Post-pandemic normalization affected entire product portfolio |
| Underperformers | Bose SoundSport generated $2,118 in 2020 as its best year | Consistently negligible demand across all years |

> 🟩 Higher Revenue | 🟥 Lower Revenue

<img src="https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/Sales%20Revenue%20by%20Product%20%26%20Year.png" width="900">

#### Key Insights

The 27in 4K Gaming Monitor is the standout revenue driver, 
peaking at $3.35M in 2021 — notably a year later than most 
products, suggesting sustained demand beyond the initial 
pandemic surge and making it the most resilient high-value 
product in the portfolio.

MacBook Air and Apple AirPods together dominated the 2020 
peak, contributing over $5.5M combined — confirming that 
premium laptops and audio products were the primary 
beneficiaries of pandemic-driven electronics demand.

All products experienced revenue contraction in 2022, 
indicating the decline is market-wide rather than 
product-specific — pointing to an external demand issue 
rather than individual product failure.

Bose SoundSport Headphones recorded negligible revenue 
across all four years, with a peak of just $2,118 in 2020 
— making it a strong candidate for discontinuation to 
free up inventory and marketing resources.


#### 2.2 Quantity by Product & Year

| Insight Area | Key Observation | Business Interpretation |
|------|-------------|-------------|
| Top Performer | Apple AirPods Headphones dominated order volume, peaking at 15,998 units in 2020 and 15,255 in 2021 | High-volume, lower-priced product drives majority of order count despite lower revenue contribution |
| Volume vs Revenue Gap | 27in 4K Gaming Monitor leads revenue but ranks 2nd in quantity | Premium pricing drives revenue despite lower unit sales |
| Consistent Decline | All products show quantity decline in 2022 | Broad market contraction affected order volumes across entire portfolio |
| Underperformers | Bose SoundSport recorded only 17 units in 2020 as its best year | Negligible demand confirms product is not resonating with customers |

> 🟩 Green = Higher Quantity | 🟥 Red = Lower Quantity

<img src="https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/Quantity%20by%20Product%20%26%20Year.png" width="900">

#### Key Insights

Apple AirPods Headphones overwhelmingly lead in order 
volume, with 15,998 units in 2020 and 15,255 in 2021 — 
far exceeding all other products. This contrasts sharply 
with the revenue ranking where the 27in 4K Gaming Monitor 
leads, highlighting that AirPods drive volume while the 
monitor drives value.

The 27in 4K Gaming Monitor ranks consistently second in 
quantity across all years despite being the top revenue 
product — confirming its premium pricing is the primary 
driver of revenue leadership rather than order volume.

Samsung Charging Cable Pack ranks surprisingly high in 
quantity (5K–7K units annually) but contributes minimally 
to revenue — indicating it is a high-volume, low-value 
accessory that inflates order counts without meaningfully 
impacting business performance.

Bose SoundSport recorded just 17 units in its best year 
(2020), dropping to a single unit by 2022 — reinforcing 
the case for product discontinuation across all metrics, 
not just revenue.

#### 2.3 AOV by Product & Year

| Insight Area | Key Observation | Business Interpretation |
|------|-------------|-------------|
| Highest AOV | MacBook Air consistently leads AOV across all years, peaking at $1,657.79 in 2019 | Premium laptop pricing drives the highest spend per transaction |
| Stable Premium | ThinkPad Laptop maintains second highest AOV (~$1,100) across all years | Laptop category consistently commands high transaction values |
| AOV vs Revenue Gap | 27in 4K Gaming Monitor leads revenue but ranks 4th in AOV at ~$430 | Volume of orders rather than price drives the monitor's revenue leadership |
| Lowest AOV | Samsung Charging Cable Pack records lowest AOV at ~$18–$22 across all years | Accessory products contribute minimal value per transaction |

> 🟩 Green = Higher AOV | 🟥 Red = Lower AOV

<img src="https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/AOV%20by%20Product%20%26%20Year.png" width="900">

#### Key Insights

MacBook Air Laptop consistently commands the highest AOV 
across all four years ($1,500–$1,657), confirming that 
laptop purchases represent the highest-value individual 
transactions in Elist's portfolio — making them critical 
to protecting AOV even as order volumes fluctuate.

ThinkPad Laptop maintains a stable second-place AOV of 
~$1,100 across all years, reinforcing that the laptop 
category as a whole anchors Elist's average transaction 
value — without laptops, overall AOV would drop 
significantly.

The 27in 4K Gaming Monitor's AOV of ~$430 reveals an 
important distinction — its revenue leadership is driven 
by consistently high order volumes rather than high 
individual transaction value, making it volume-dependent 
and therefore more sensitive to demand shifts.

Samsung Charging Cable Pack records the lowest AOV at 
$18–$22 across all years — while it contributes to order 
count, its near-zero impact on revenue and AOV suggests 
it functions more as an add-on accessory than a 
standalone revenue driver.


#### 2.4 Refund Rate by Product & Year

| Insight Area | Key Observation | Business Interpretation |
|------|-------------|-------------|
| Highest Refund Rate | MacBook Air (18.31%) and ThinkPad (17.00%) recorded the highest refund rates in 2019–2020 | Premium laptops carry higher return risk, likely due to price sensitivity and quality expectations |
| Sharp Decline | All products recorded 0.00% refund rate in 2022 | Possible data gap or change in refund tracking methodology — requires verification |
| Improving Trend | Refund rates dropped significantly from 2020 to 2021 across all products | Improved product quality, customer expectations alignment, or stricter return policies |
| Low Refund Products | Samsung Charging Cable Pack consistently records lowest refund rates | Low-cost accessories have minimal return motivation |

> 🟩 Green = Higher Refund Rate | 🟥 Red = Lower Refund Rate

<img src="url" width="900">

#### Key Insights

MacBook Air and ThinkPad Laptop recorded the highest 
refund rates of 18.31% and 17.00% respectively in 
2019–2020 — likely reflecting high customer expectations 
for premium products and price sensitivity at the $1,500+ 
price point. This warrants closer investigation into 
return reasons to protect revenue integrity.

Refund rates improved substantially across all products 
from 2020 to 2021, suggesting either improved product 
quality, better pre-purchase customer education, or 
tightened return policies following the high-refund 
pandemic period.

All products show 0.00% refund rate in 2022 — this is 
unusual and likely reflects a data collection issue 
rather than a genuine elimination of refunds. This 
should be flagged and verified before drawing any 
conclusions from 2022 refund data.

Bose SoundSport Headphones recorded 0.00% refund rate 
across most years — however given its negligible sales 
volume, this metric is statistically insignificant and 
should not be interpreted as a quality indicator.





















         
   ### 3. Loyalty Program Evaluation ###
      1. Evaluation Focus
      2. Key findings
      3. Recommendations
   ### 4. Regional Performance Analysis ###
      1. Regions Analyzed
      2. Key Findings
      3. Recommendations
      
4. Business Impact & Next Steps
   1. Overall Insights
   2. Future Enhancements
      
        
        
