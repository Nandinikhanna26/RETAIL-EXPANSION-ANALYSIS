#  SQL-Driven Retail Expansion Strategy

This project delivers 12 data-backed insights for scaling a coffee retail business. Using SQL on a mock dataset, we explored customer behavior, revenue trends, and product performance — all geared toward identifying key areas for growth and operational focus.

---

## 1 Market Sizing by City – Estimating Demand Potential

Estimated the coffee-drinking population in major cities (assuming 30% of total population).

**Takeaway:**  
Delhi, Mumbai, and Kolkata show the highest consumer base — ideal markets for expansion or targeted promotions.

** Visual:**  
![Insight 1](https://github.com/Nandinikhanna26/RETAIL-EXPANSION-ANALYSIS/blob/main/Insight1.png)

---

## 2 Seasonal Revenue Spike – Q4 2023 Performance

Measured revenue during Oct–Dec 2023 to understand seasonal impact.

**Takeaway:**  
Q4 generated ₹1.96M in revenue — highlighting a strong year-end boost worth aligning future campaigns with.

** Visual:**  
![Insight 2]([IMAGE_LINK_HERE](https://github.com/Nandinikhanna26/RETAIL-EXPANSION-ANALYSIS/blob/main/Insight2.png))

---

## 3 Regional Performance – Top Revenue Cities (Q4)

Ranked cities by total Q4 revenue contribution using customer and sales data.

**Takeaway:**  
Pune, Chennai, and Bangalore led revenue figures — prime candidates for deeper market investment.

** Visual:**  
![Insight 3](IMAGE_LINK_HERE)

---

## 4 Product Demand – Best Sellers by Order Volume

Identified top-performing products across all sales.

**Takeaway:**  
Cold Brew 6-Pack is the top seller, followed by Ground Espresso. High performers can lead bundling or ad campaigns.

** Visual:**  
![Insight 4](IMAGE_LINK_HERE)

---

## 5 Revenue & Customer Distribution by City

Analyzed total revenue, unique customer count, and average revenue per customer across cities.


**Takeaway:**  
Pune, Chennai, and Bangalore lead in both total revenue and customer base. Jaipur stands out for its high average spend per customer — indicating potential for premium product positioning in smaller cities.

** Visual:**  
![Insight 3](IMAGE_LINK_HERE)


---

## 6 City-Wise Market Potential vs. Actual Reach

This analysis compares the estimated number of potential coffee consumers (calculated as 30% of the city population) with the actual number of unique customers from each city. The goal is to identify underserved markets and assess current market penetration city-wise.

**Takeaway:**  
Metro cities such as **Delhi** and **Jaipur** show strong customer bases, yet still fall short of their full market potential—indicating room for deeper penetration. On the other hand, **Ahmedabad**, **Indore**, and **Kanpur** are highly underpenetrated, representing strong opportunities for market entry or expansion strategies.

**Visual:**  
![Insight 6](IMAGE_LINK_HERE)

---

## 7 City-Wise Top-Selling Products

This analysis identifies the top-selling products in each city using the DENSE_RANK() window function. Products are ranked based on the number of total orders in their respective cities. This helps us understand regional preferences and consumer behavior more clearly.

**Takeaway:**  
This ranking reveals product demand by location. For instance, in Ahmedabad, top choices include Cold Brew Coffee Pack, Coffee Beans (500g), and Instant Coffee Powder. These insights can guide regional inventory planning, targeted product campaigns, and localized bundling strategies.

** Visual:**  
![Insight 3](IMAGE_LINK_HERE)


---

## 8 Top 3 Products by City

This query identifies the top 3 best-selling products in each city using a DENSE_RANK() window function, helping pinpoint product-level preferences across regions.

**Takeaway:**  
This insight uncovers city-specific favorites. For example, cities like Bangalore, Chennai, and Delhi show a common preference for Cold Brew Packs and Instant Coffee Powder, suggesting a strong demand for convenient and ready-to-drink formats. Use this to drive localized merchandising and tailored promotions.

** Visual:**  
![Insight 3](IMAGE_LINK_HERE)


---

## 10 Unique Customers by City (Selected Products)

This insight counts the number of unique customers from each city who purchased any of the 14 key products, helping identify geographic demand concentration for strategic targeting.


**Takeaway:**  
Jaipur, Delhi, and Pune show high engagement among customers for the selected product portfolio, making them ideal cities for product bundling strategies or early access campaigns. Meanwhile, cities like Indore, Hyderabad, and Ahmedabad offer room for customer acquisition efforts.

** Visual:**  
![Insight 3](IMAGE_LINK_HERE)


---

## 12 Average Rent per Customer vs. Revenue per Customer

This insight combines estimated city rent costs with average revenue per customer to assess the cost-efficiency of operations in each city.


**Takeaway:**  
Cities like Mumbai, Hyderabad, and Bangalore show a high average rent per customer, posing operational cost challenges despite decent revenues. In contrast, Jaipur and Pune demonstrate favorable rent-to-revenue ratios, making them more viable for physical expansion or flagship stores.



** Visual:**  
![Insight 3](IMAGE_LINK_HERE)


---
