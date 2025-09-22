# 📊 Shopee Sales Data EDA (May 2023) – Cross Border eCommerce Insights

This project is a quick exploratory data analysis (EDA) of Shopee’s publicly available sales data from **April–May 2023**, focusing specifically on products listed in **May 2023**. The goal is to extract meaningful insights for cross-border operations, category performance, and seller optimization — aligned with Shopee's Cross Border eCommerce team objectives.

> 📁 Dataset Source: [Sh](https://www.kaggle.com/datasets/yoongshiuan/shopee-sales-dataset-aprilmay-2023)  
> 🔍 Focus: Product listings, category revenue, seller location, and market performance.


## Objectives

- Analyze product listing trends and seller activity in May 2023
- Identify high-performing categories by volume and revenue
- Extract location-level sourcing insights (local vs. cross-border)
- Provide actionable takeaways for project optimization and cross-border enablement

---

## Key Findings

### 1. Products Crawled Per Day
- Peak crawl date: **May 1st, 2023** (3,646 products listed)
- Remaining dates show steady, smaller volumes
- Could reflect batch release, sale cycle, or crawler scheduling
  
<img width="1031" height="503" alt="Screenshot 2025-09-22 at 2 38 00 PM" src="https://github.com/user-attachments/assets/f1bddfcb-5eaf-4be2-8300-208826f47429" />

### 2. Listings by Seller Location
| Location        | Listings |
|----------------|----------|
| Selangor        | 5,856    |
| Oversea         | 2,661    |
| Kuala Lumpur    | 2,418    |
| Johor           | 1,228    |
| Perak           | 1,137    |

> 🔎 Cross-border sellers accounted for ~23% of listings — opportunity for performance segmentation and targeted regional fulfillment strategy.


<img width="828" height="489" alt="Screenshot 2025-09-22 at 2 35 56 PM" src="https://github.com/user-attachments/assets/16ad3913-ebcc-4247-be2e-11c0eb18384b" />

## Category Analysis

### 3. Product Counts by Main Category
| Main Category           | Count |
|-------------------------|-------|
| Men Clothes             | 1,963 |
| Health & Beauty         | 1,931 |
| Women Clothes           | 1,729 |
| Mobile & Accessories    | 1,476 |
| Baby & Toys             | 1,322 |

<img width="814" height="481" alt="Screenshot 2025-09-22 at 2 36 23 PM" src="https://github.com/user-attachments/assets/040098b7-5559-4eeb-bcd6-5d489e1942e4" />



### 4. Subcategory Trends (Top 3 Categories)

**Men Clothes**  
- Top Subcategories: Sets, Suits, Shirts

**Health & Beauty**  
- Top Subcategories: Bath & Body, Foot Care, Eye Make Up

**Women Clothes**  
- Top Subcategories: Sportswear, Outerwear, Tops

---

### 5. Price Range by Category
| Category               | Min (MYR) | Max (MYR) | Avg Price (MYR) |
|------------------------|-----------|-----------|-----------------|
| Automotive             | 0.00      | 205,500.00| 4,521.18         |
| Baby & Toys            | 0.00      | 99,999.00 | 221.05           |
| Cameras & Drones       | 0.10      | 28,451.80 | 934.49           |
| Fashion Accessories    | 0.10      | 999.00    | 22.21            |

>  Wide price variance in Automotive and Baby categories — outliers and bundled listings should be further investigated.

---

### 6. Revenue by Main Category
| Main Category           | Revenue (MYR) |
|------------------------|---------------|
| Home Appliances         | 214.8M        |
| Health & Beauty         | 174.6M        |
| Mobile & Accessories    | 130.9M        |
| Baby & Toys             | 129.7M        |
| Groceries & Pets        | 87.6M         |

> Top revenue categories are not always top in listing volume — product mix and pricing strategies are critical in CBEC.

<img width="1023" height="509" alt="Screenshot 2025-09-22 at 2 36 45 PM" src="https://github.com/user-attachments/assets/26a411d4-70b7-4255-80e9-c61645b8f17a" />


##  Relevance to Shopee Cross Border eCommerce

This analysis directly supports tasks related to:
- Business performance tracking
- Cross-border seller segmentation
- Category-level opportunity sizing
- Process optimization and insights reporting

---

## Tools Used

- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Jupyter Notebook
- Dataset: CSV format from Kaggle
