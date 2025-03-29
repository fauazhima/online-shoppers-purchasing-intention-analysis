# **Online Shoppers Purchasing Intention Analysis for Offbrand Inc. 🛍️**
---
Analysis of online shoppers purchasing intention dataset for Offbrand Inc. using Python and Tableau.

## **Background**
---
*Below is a fictious scenario aimed for data analysis practice*

Offbrand Inc. is a streetwear clothing brand based in the US that focuses on making clothes that are unique and authentic, aiming to redefine the standards of the fashion industry in the world. They have been selling their product through retail stores around the US for the last 5 years, and are looking to expand their operation through online e-commerce platform like Amazon. However to do this, they need to learn more about online shoppers purchasing behavior to come up with an effective online marketing and sales strategy. *Offbrand Inc. needs to analyze online shopper behavior to address gaps in purchasing trends, browsing habits, and cart abandonment, ensuring a data-driven strategy to achieve its online store goals by the end of the year.*

## **Dataset**
---
The dataset used for this analysis is extracted from [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset). It comprises of 12330 instances with 17 features, providing a robust foundation for analysis for the sake of Offbrand's e-commerce expansion.

The following are the features that can be found within the dataset:
### **I. Website Interaction Metrics**
| Name | Description |
| -------- | ------- |
| Administrative | Number of pages related to administrative tasks visited by the user |
| Administrative_Duration | Total time spent on administrative pages by the user |
| Informational | Number of pages related to informational pages visited by the user |
| Informational_Duration | Total time spent on informational pages by the user |
| ProductRelated | Number of product pages and the likes visited by the user |
| ProductRelated_Duration | Total time spent on product-related pages by the user |
| BounceRates | Percentage of visitors who leave the site after viewing only one page |
| ExitRates | Percentage of visitors who leave the site after viewing a specific page |
| PageValues | Value of pages in monetary terms |
| Revenue | Indication of whether or not the user completed their purchase |

### **II. User Information**
| Name | Description |
| -------- | ------- |
| VisitorType | Type of visitor (e.g.: Returning Visitor, New Visitor) |
| OperatingSystem | OS of the user (encoded as integer) |
| Browser | Browser used by the user (encoded as integer) |
| Region | Geographical location of the user (encoded as integer) |
| TrafficType | Source of user's traffic to the website (encoded as integer) |

### **III. Temporal Features**
| Name | Description |
| -------- | ------- |
| Month | Month in which the user visited the website |
| Weekend | Indication of whether or not the visit occured on a weekend |
| SpecialDay | Indication of whether or not the visit occured on a holiday |

## **Objectives**
---
This analysis is aimed to:
- Identifying and analyzing trends for online shopper purchasing behavior, includes factors influencing purchase decision, browsing habits, session length, and cart abandonment rates.
- Helping Offbrand Inc. expand smoothly to e-commerce.

## **Methodology**
---
The analysis is done in order as follow:
1. **Data Cleaning and Preprocessing**: Checking for missing values, handling anomalies, removing duplicates, and preparing data for analysis.
2. **Exploratory Data Analysis (EDA)**: Identifying trends and patterns in the dataset.
3. **Data Visualization**: Using Tableau for to visualize findings with interactive features.

## **Visualization**
---
[Click here](https://public.tableau.com/views/OnlineShoppersPurchasingIntention_Dashboard/Customer?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) for the link to the Tableau dashboard

## **Conclusion and Recommendation**
---
The analysis highlights several findings regarding users' purchasing intetion online. First, it highlights the significant peaks and dips in transaction counts and user sessions within this dataset's period, where we see a very similar but not the same trend. Then, we see a positive correlation between bounce rates and exit rates only between 0% to 20%, which means that all pages were consistent in their performance to keep users from exiting their page. Then, we learned that Product-Related pages are where users will end up on most of the time, which means that these pages are the KEY to conversions. Analysis also shows that non-special days are when people tend to check out online shops the most instead of special days. 

According to the analysis, the following are what I would recommend Offbrand Inc.:
- **Enhancing Product-Related Content**: As product pages are where online users look the most for in an online shop, Offbrand Inc. should look to invest the most time optimizing these pages for their online store. 
- **In Promotions, Timing is Key**: Offbrand Inc. should always be on the look-out for the best time to schedule their promotions. Because as we can see, it does convert to user transaction and user sessions, especially in seasonal sales in the US like Black Friday.
- **Campaigns Should be Done in Low Points**: Why is this? Because dips are where people are least interested, Offbrand Inc. should learn from this dataset and create an effective campaign that sparks new interests when there isn't any, which in the long run will help stabilize revenue gains from even the lowest points of user transaction.
- **Exclusive Deals on Special Days**: People should have a reason to buy during Special Days, so that even during Special Days, users are still interested in visiting their website. This is best done by creating exclusive deals / products during Special Days.
- **Research on Outliers in Bounce Rates and Exit Rates**: By doing this, Offbrand Inc. will have a better understanding why some pages are clicked off more than others and improve based on that information.

## **Author**
---
Hello! My name is Fauzan Azhima Achmad, and I created this notebook for the purpose of exploring the dataset in order to solve a fictious yet realistic problem that persists in the real world. If you like my analysis, consider following me on [LinkedIn](https://www.linkedin.com/in/achmadfauzanazhima/)!
