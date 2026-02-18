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
   
   From a regional perspective, North America emerged as the dominant market, accounting for 51.75% of total revenue across all years. In contrast, APAC and LATAM demonstrated comparatively lower demand and 
   higher variability in product performance, signaling opportunities for targeted regional strategies and deeper market penetration.
   

   Analysis of customer behavior revealed meaningful growth in loyalty program adoption, rising from 12% membership in 2019 to over 50% by 2021, with loyalty members showing higher repeat purchase rates than non-members. 
   However, the relatively modest $30 AOV gap between loyalty and non-loyalty customers suggests the program may benefit from stronger incentives and personalization to drive deeper engagement and long-term retention.

   Overall, the analysis highlights Elist’s reliance on premium products for revenue growth, the strong performance of the North American market, and clear opportunities to enhance loyalty program effectiveness and 
   regional sales strategies.

### 2. Insights Deep Dive ###
#### 1. Sales Trends Analysis ####


| Insight Area | Key Observation | Business Interpretation |
|------|-------------|-------------|
| YoY Growth | 2020 shows strong YoY growth across most months, while 2022 shows consistent YoY decline | Indicates post-pandemic peak in 2020 followed by demand normalization in 2022 |
| Seasonality | Sales peak during Aug–Dec across multiple years | Q3–Q4 are critical revenue-driving periods |
| Volatility | Large MoM fluctuations observed, especially in 2021 | Reflects external shocks and recovery cycles impacting revenue |

| Sales Revenue YoY | Sales Revenue MoM |
|------------------|------------|
| ![Alt Text](https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/YoY%20of%20Sales%20Revenue.png)|![Alt Text](https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/MoM%20of%20Sales%20Revenue.png)|



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


| Orders YoY | Orders MoM |
|------------------|------------|
|![Alt Text](https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/YoY%20of%20Orders.png)|![Alt Text](https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/MoM%20of%20Orders.png)|


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

| AOV YoY | AOV MoM |
|------------------|------------|
|![Alt Text](https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/YoY%20of%20AOV.png)| ![Alt Text](https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/MoM%20of%20AOV.png)|



#### Key Insights ####

AOV is significantly more stable than sales or orders, making it a reliable efficiency metric.

Declining AOV in 2021 suggests aggressive promotions or changes in product mix to drive volume.

Partial AOV recovery in 2022 indicates improved pricing discipline or customer purchasing behavior.


      
### 2. Product Performance Analysis ###
| Insight Area | Key Observation | Business Interpretation |
|------|-------------|-------------|
| Sales Revenue | The 2.7in 4k Gaming Monitor is the top-performing products, generating $9.8M in total revenue, consistently strong year-over-year performance. Apple Airpod Headphones ($7.7M) and Macbook Air Laptop ($6.29M) rank as second and third highest revenue contributors.The Bose SoundSport Headphones significantly underperformed, generating only $3339 in total sales, with no recorded sales in multiple months, indicating exteremly low demand.Apple iPhone is the second lowest revenue performer, with $213k in total sales.|Revenue is highly concentrated around a small number of products. High ticket and premium electronics drive the majority of sales, while several products contribute minimal revenue. Under performing products shows sign of weak demand and inconsistent sales patterns.|Proritizing top performing products in marketing and inventory planning. Evaluate whether low performing products ( Bose Soundsport, iphone) should be repositioned, discounted, bundled or discontinued. Explore bundling accessories with high performing products to maximize overall sales.|
| Orders Quantity | Strong and consistent Q3 and Q4 sales spikes are observed across products, driven by Holiday shopping. The 2.7in 4k Gaming monitor, Samsung Charging cable pack and apple airpods shows the largest Q4 order surge, reinforcing the their role as seasonal bestsellers. Sales typically dip in Jan and Feb, reflecting post holiday demand slowdown. Macbook Air, Thinkpad laptops demonstrate consistent baseline demand, with stable order volume throughout Q2 and Q3, though lower than Q4 peaks. Order volume is highly seasonal, with Q4 driving a disproportionate share of annual orders. Core products maintaine steady demand year over year making them reliable revenue anchors. Non-core products shows negligible order activity.| Alignn inventory and marketing strategies to captialize on Q4 demand spikes. Use Q1 promotions to smooth post holiday sales declines. Focus on product expansion and cross selling around consistently demanded products.|
| AOV | AOV peaked in 2020 at $300.16, driven by increased demand for high ticket items during the pandamic. AOV declined in 2021($254.71) and 2022 ($229.91), reflecting post pandamic normalisation. The Macbook Air ($1588.12), Thinkpad Laptop ($1099.56) and apple iphone ($740.72) are the largest contributors to AOV, due to high price point. Low cost products such as the Samsung Charging Cable pack ($20.20) and Samsung Webcam ($50.43) maintain stable sales but have minimal impact on AOV.| AOV is heavily influenced by premium products mix, not pricing chnages. Reduced demand for high ticket items directly lower AOV Lower priced accessories provide volume stabilty but not materially improve revenue per order.| Provide incentives on high AOV products through finiancing options, limited time offers, or loyalty program rewards. Use accessories as add on rather than standalone sales to lift AOV Promote laptop and monitor bundles during peak season to stabalize AOV.|
| Refund Rate |Most Refunded Products: Bose Soundsport Headphones, Samsung Charging Cable Pack, and Samsung Webcam show the highest refund rates. Least Refunded Products: MacBook Air Laptop and ThinkPad Laptop consistently rank among the lowest in refund rates. Apple AirPods Headphones maintain a relatively consistent refund rate year over year. Accessories tend to have higher historical refund rates than laptops. Refund rates steadily decline from 2019 to 2022.  | Accessory and electronics add-ons may face higher compatibility or quality issues, requiring better product descriptions and QA checks. High-value products show stronger customer satisfaction and confidence, supporting continued focus on premium product offerings.|


#### Product Performance by Northstar Metrics: ####
![Alt Text](https://github.com/mrunalibharshankar/Elist-Retail-Analysis-Orders-to-Insights/blob/main/Product%20Performance.png)
         
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
      
        
        
