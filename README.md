### Problem Description : Sales forecasting of a pharmaceutical retail chain
 KioMed, a huge pharmaceutical retailer, operates in in 10+ cities across India. The company has one distribution warehouse in each of the cities it operates in. Unfortunately, the warehouses are not able to consistently meet the demand of the stores in their respective cities. Kio, the parent company, being a data driven corporation wants to solve the stocking / inventory management problem using their in-house data science team.

The retailer has provided you with historical sales data and is looking to forecast the sales for the period of one month after the end of the data. These forecasts will be used to ensure that the company is able to stock its supplies of medicines in a warehouse accordingly in each city for a period of one month.

The company will also provide you with the footfall data for all the stores across each of its cities. You can use this data, but as in the case of the real world, the footfall data is only available at train time and not at test time

### Approach

1. Read the data
2. Explore all the available features from  all the different files in different formats
3. check for duplicate files and comeup with an approach for merging all the files with required features
4. check for duplicates before merging the files
5. if duplicates are present explore the data which is having duplicates or outliers discuss with domain expert to come up with conclusions
