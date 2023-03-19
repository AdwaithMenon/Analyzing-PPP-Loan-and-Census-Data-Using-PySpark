# _**Analyzing PPP Loan and Census Data Using PySpark : A Comprehensive Exploration**_


## **Project Description**

The aim of this project is to conduct a comprehensive exploration of the PPP loan data and census data using PySpark, a distributed computing framework for big data processing. The study involves analyzing the datasets to identify any correlations, patterns, or trends that may exist between them. The analysis will involve data cleaning, integration, and transformation to provide a comprehensive understanding of the datasets. The project's findings will be useful for policymakers, business owners, and researchers interested in understanding the impact of PPP loans on different demographic groups and local economies. 

## **Observations**

### **a) Top 10 States that Received Loans**

<img width="304" alt="image" src="https://user-images.githubusercontent.com/70052374/226200781-8f9bee3f-6e49-4717-92fb-742d8b39b6f0.png">


* The Top 10 States that received loans are California, New York, Texas, Florida, Illinois, Pennsylvania, Ohio, New Jersey, Michigan and Colorado.


### **b) Percentage of Foreign Born vs Native Born Population for Top 100 Zip Codes that Received Loans**

**i)**
<img width="317" alt="image" src="https://user-images.githubusercontent.com/70052374/226200980-ddcb80c3-5fb9-47da-bd64-16a7563fd74c.png">


**ii)**
<img width="326" alt="image" src="https://user-images.githubusercontent.com/70052374/226201001-d8e63e22-9c60-45e0-abcd-d8337770b9a7.png">


* *By analyzing Histograms **i and ii**, it is evident that the Top 100 Zip Codes that received the highest amount of money are predominantly those where the Percentage of Native Population is over 60% and the Percentage of Foreign Born Population is below 40%.*

* *It appears that Zip Codes with a higher Percentage of Native Population have received a larger amount of loans, and there could be several reasons for this trend.*

* *One reason for this could be that secured loans require collateral to be pledged in order to secure the loan, and Native people may have more assets available to use as collateral compared to Foreign Nationals.*

* *An additional factor could be that certain types of loans may have citizenship requirements, particularly for loan amounts above a certain limit. This may limit access to loans for Foreign Nationals who are not U.S. citizens or permanent residents.*

* *The third and perhaps most significant reason is that building a good credit history is crucial for obtaining larger loan amounts. As it takes time to establish a strong credit score, Native people may have an advantage over Foreign Nationals in this regard and may be more likely to have higher credit scores, making them more eligible for larger loans.*


### **c)**
