# FMCG-Sales-Dashboard-With-Power-BI
**Requirements:**
![image](https://user-images.githubusercontent.com/118095331/219083274-37f73351-6690-4cbe-bb73-f7398ece5674.png)

In this project, I conducted an in-depth analysis and visualized the sales data from a FMCG brand. To be more specific, while the reporting involves capturing of general sales figures and detailed information based on Month/Year, Products, Channels and Geography, the analysis will focus on providing information about Sales value and Growth rate as the requirements stated. 

## Step 1: Data Importing & Transforming 

From my experience, I always want to look into the files before importing them. In this case, the data was stored in folers and the files are divided into quarters and year halfs, which means I would use folder import to combine the files.
![1](https://user-images.githubusercontent.com/118095331/219263663-f5628770-06e4-46e2-96c7-e8b96aa36b39.png)

Next, I imported the data into Power BI and began to transform them. When it comes to transfoming the data, I always began with removing any null rows, promoting headers, making sure that the data type in each column was correct and removing duplicates. Adding new column(s) would depend on different cases. In this case, for FACT GT SALES table, I add the column "Thành phố" by spliting from the column "Địa chỉ"(Address).   

![2](https://user-images.githubusercontent.com/118095331/219308481-1259c40e-e0eb-4b4e-a724-082fea92ff41.png)

It was very essential to name and create Fact tables and Dim tables for the data modeling later.

![image](https://user-images.githubusercontent.com/118095331/219308886-378e0a95-5610-48ea-adb6-ddab8f64d67b.png)

## Step 2: Data Modeling

After I had all the Fact and DIM tables listed, it was very easy to create relationships in the data modeling and I could get into visualizing the data right away.

![image](https://user-images.githubusercontent.com/118095331/219309400-74b8e559-11a4-422f-a420-63e0b18354da.png)

## Step 3: Data Visualizing
In this step, I analyzed the requirements and provided clear and concise answers to the questions using one to two pages.

**Reporting - Overview: Total Sales Value & Growth rate**  

![image](https://user-images.githubusercontent.com/118095331/219313082-73624bf6-6b58-4e00-98dd-69273fb406ee.png)

Between 01/01/2020 and 30/06/2021, the brand generated a total sales value of 6.239 million. Out of this, the GT (General Trade) channel contributed 2.899 million while the MT (Modern Trade) channel contributed 3.421 million. Additionally, the year-to-date growth rate was 11.26%. The Sales Value by Month chart shows a positive correlation between 2020 and 2021. However, the biggest divergence occurred in May 2021, where sales were 110,156,000 higher compared to May 2020. In general, the MT channel had higher sales value than the GT channel. However, from March 2021 onwards, the GT channel took the lead. The product "VÁNG SỮA" had the highest sales value of 4,292,640,000, accounting for almost 70% of the brand's total sales value. It was followed by SỮA UỐNG with 1,299,600,000 and PHÔ MAI ĂN LIỀN with 737,058,000. Across all 30 cities, the sale values ranged from 960,000 to 1,876,780,000.

**Reporting - By Month/Year**
  
![image](https://user-images.githubusercontent.com/118095331/219313930-47889cdd-62d5-4538-b032-3cf9526b5680.png)

On a closer examination of the timeline, both GT total sales (58.11% increase) and MT total sales (24.48% increase) showed an upward trend between January 2020 and June 2021. In 2020, July had the highest sales value at 422,332,000, representing a 44.18% increase compared to November, which had the lowest sales value at 292,921,000. July also accounted for 10.38% of the total sales value in 2020. In 2021, May had the highest sales value at 443,229,000, which was 54.62% higher than February, the month with the lowest sales value at 286,660,000. May also accounted for 19.61% of the total sales value in 2021.


**Reporting - By Product**  

![image](https://user-images.githubusercontent.com/118095331/219316832-c61b07f5-da11-413e-8712-43beee97775c.png)  

In general, VÁNG SỮA had the highest total sales value at 4,292,640,000, accounting for almost 70% of the total sales. It was followed by SỮA UỐNG at 1,299,600,000 and PHÔ MAI ĂN LIỀN at 737,058,000. Furthermore, the growth rate of "Phô Mai Ăn Liền", "Sữa Uống" and "Váng Sữa" was 42.38%, 27.82% and 2.03% respectively. As we can see, SALES VALUE and total GROWTH RATE are negatively correlated with each other when it comes to the products.

**Reporting - By Channel**  

![image](https://user-images.githubusercontent.com/118095331/219318788-f0c4fb7d-e040-4e8b-9bee-28882b61c7d1.png)

Regarding sales value, the MT channel had the highest sales value of 3,431M, accounting for more than 54% of the total sales value. However, when it comes to growth rate, the GT channel showed a significant performance with a growth rate of 21.44%, compared to 2.99% of the MT channel. In both MT and GT channels, "Váng Sữa" was the best-selling product with 2,182 million and 2,165 million sales value, respectively. However, while the second best-selling product in the MT channel was "Phô Mai Ăn Liền", the second best-selling product in the GT channel was "Sữa Uống". Across all 30 cities, the MT sales value ranged from 960,000 to 1,876,780,000. HA NOI had the highest MT sales value at 1,876,780,000, which was 195,397.92% higher than LONG AN, the city with the lowest MT sales value at 960,000. On the other hand, DA NANG accounted for 58.49% of the GT sales value, with 1,695,333,000 GT sales value. TP HCM had 1,063,002,000, and LANG SON had 140,166,000. 

**Reporting - By Geography**  

![image](https://user-images.githubusercontent.com/118095331/219323070-89d4d2d3-a9b0-45c2-bc3c-99d42b768fa3.png)

As observed, the largest sales value in the GT channel was contributed by DA NANG with 1,695 million, whereas HANOI was the biggest contributor to the MT channel with 1,877 million in sales value. The most notable highlight is that despite having a sales value of only 142 million, LANG SON had a growth rate of 11155%. This could be attributed to the fact that the city had very low sales in 2020, potentially only for testing purposes, and the actual sales of the brand in LANG SON began in 2021.

![image](https://user-images.githubusercontent.com/118095331/219332817-ba049688-e28b-4999-9d41-ff865aa1b586.png)

**Analysis - Channel & Geography**  

**Questions:**   
![image](https://user-images.githubusercontent.com/118095331/219334458-38cde146-66df-4ebc-9349-bd57a454177a.png)



![image](https://user-images.githubusercontent.com/118095331/219333300-6b5baec8-8254-4a9d-b1e2-622eb6040e85.png)


**Analysis - Ad-hoc(1)**

**Analysis - Ad-hoc(2)**
