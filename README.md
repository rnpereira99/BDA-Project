<h1>Big Data Analytics Project</h1>

## 1.1. Business Background

The retail industry is undergoing a significant transformation. Online retail shopping has become an absolute necessity to compete for business, and with that change comes new challenges, especially in niche areas such as gift items. As customer expectations rise and buying habits become more complex, retailers can no longer rely solely on intuition to gauge demand or manage inventory. They must become data-driven.

The company is a UK-based online retailer of giftware, primarily serving wholesale customers. This segment of the business has additional operational complexities, including high-volume purchases, unpredictable seasonality (especially during the holiday season), and a customer base divided between loyal repeat buyers and one-time, resourceful purchasers. What appears to be a simple transaction flow is in fact a rich and dynamic stream of behavioral data waiting to be deciphered.

In this environment, traditional data tools are not enough. Forecasting demand and understanding customers requires a scalable and intelligent approach. This project reflects how large companies are beginning to process huge, fast-moving data sets. Even though the current dataset is limited in size, it mirrors the volume, velocity, and variety challenges faced by growing online retailers.

## 1.2. Business Objectives

The overarching goal of this project is to empower a growing online retailer with the analytical tools needed to make smarter, data-driven decisions in two critical areas: customer understanding and demand forecasting.

### Customer Segmentation

The first objective is to uncover meaningful customer segments based on purchasing behavior. Not all customers bring the same value or behave in the same way - some make frequent low-volume purchases, others buy in bulk seasonally, and some show irregular patterns that suggest churn risk or opportunistic buying. 

By applying clustering techniques, we aim to:
- Identify distinct customer personas (e.g., "Loyal Wholesalers", "Occasional Retailers", "Holiday Shoppers")
- Reveal behavioral patterns that can inform targeted marketing and personalized recommendations
- Provide insights to improve customer retention and customer lifetime value (CLV)

This segmentation can serve as the foundation for a more customized engagement strategy, allowing retailers to move away from one-size-fits-all campaigns toward data-driven personalization.

### Sales Forecasting

The second objective is to develop a predictive model that estimates future sales based on historical transaction data.

Accurate forecasting is essential for:
- Optimizing inventory levels and reducing both stockouts and overstock situations
- Aligning operational planning with expected demand spikes (e.g., during the holiday season)
- Informing pricing, promotional, and procurement strategies

By implementing time-series forecasting models, we will simulate a pipeline that can eventually evolve into a real-time prediction engine in a production environment.

## 1.3. Delivery: Promoting Data Culture

As a fun and creative twist, we also plan to write an internal promotional article titled something like:  
**"How Big Data Knows When Your Aunt Buys That Weird Candle Set Every Christmas"**  

This lighthearted piece will explain our results in plain language to non-technical employees - demonstrating how customer insights and predictive analytics can revolutionize operations, and inspiring a company-wide embrace of digital transformation and data culture.

## 1.4. Business Success Criteria

Success for this project will be evaluated using both **quantitative** and **qualitative** criteria:

### Quantitative Criteria
- **Clustering Performance**: Metrics such as silhouette score, Davies-Bouldin index, or within-cluster sum of squares (WCSS) will be used to assess the quality of customer segmentation.
- **Forecast Accuracy**: Measured using MAE (Mean Absolute Error), RMSE (Root Mean Squared Error), and MAPE (Mean Absolute Percentage Error) on sales predictions.
- **Actionable Insights**: The identification of at least 3 meaningful and distinct customer segments, and 1-2 sales forecasting trends that could support operational decisions.

### Qualitative Criteria
- **Interpretability**: Clear and intuitive visualization of clusters and forecast trends for presentation to non-technical stakeholders.
- **Engagement**: The fun internal article should effectively raise awareness about the value of data analytics and be positively received by company staff.
- **Scalability Potential**: The approach should be adaptable to larger datasets and scalable for production-level deployment in a real business context.

By combining rigorous analytics with creative storytelling, this project aims not only to deliver strategic insights but also to shift the company mindset toward becoming truly data-driven.

## 2. Metadata

| Features | Descriptions |
|---------|---------------------|
| *ID* | Customer ID |
| *Invoice* | Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation. |
| *StockCode* | Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product. |
| *Description* | Product (item) name. Nominal. |
| *Quantity* | The quantities of each product (item) per transaction. Numeric. |
| *InvoiceDate* | Invoice date and time. Numeric. The day and time when a transaction was generated. |
| *Price* | Unit price. Numeric. Product price per unit in sterling (Â£). |
| *Customer ID* | Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer. |
| *Country* | Country name. Nominal. The name of the country where a customer resides. |


##
