# Tokyo-Olympic-Data-Engineering-Project
### Project Architecture : 
![image](https://github.com/abhi-nilekar/Tokyo-Olympic-Data-Engineering-Project/assets/24265534/43f8c5e1-de4d-4be3-8445-3328cb852df3)


1. **Data Integration**: In the first stage of the project, I integrated data from various sources using Azure Data Factory. This tool allowed me to create data-driven workflows for orchestrating and automating data movement and data transformation.
![image](https://github.com/abhi-nilekar/Tokyo-Olympic-Data-Engineering-Project/assets/24265534/d40e7420-c4b1-458f-9b06-53af4ada73f2)

2. **Raw Data Storage**: After integrating the data, I stored it in a raw data store. For this, I used Azure Data Lake Storage Gen2 which provides secure, scalable, and cost-effective storage.
![image](https://github.com/abhi-nilekar/Tokyo-Olympic-Data-Engineering-Project/assets/24265534/173532d4-202b-4085-9b8b-f53bdec81a68)

3. **Data Transformation**: The next step was to transform the data to make it suitable for analysis. I used Azure Databricks for this purpose, which is an Apache Spark-based analytics platform optimized for Azure. It allowed me to transform large volumes of data and make it ready for analysis.
![image](https://github.com/abhi-nilekar/Tokyo-Olympic-Data-Engineering-Project/assets/24265534/fe763eac-c37b-4857-b686-d03098e468cc)

4. **Transformed Data Storage**: I stored the transformed data back into Azure Data Lake Storage Gen2. Storing the transformed data separately ensures that the raw data remains untouched and can be used again if needed.
![image](https://github.com/abhi-nilekar/Tokyo-Olympic-Data-Engineering-Project/assets/24265534/62d027e2-b01c-4825-b17a-7783b1082e3e)

5. **Data Analysis and Visualization**: Finally, I analyzed the data and created a dashboard to visualize it. I used Azure Synapse Analytics, an integrated analytics service, for analyzing the data. For visualization, I used Power BI which helped me create comprehensive dashboards and reports.
![image](https://github.com/abhi-nilekar/Tokyo-Olympic-Data-Engineering-Project/assets/24265534/23e26acc-986d-4457-bd2e-ee5d516d0141)

6. **Power BI report** :

   ![image](https://github.com/abhi-nilekar/Tokyo-Olympic-Data-Engineering-Project/assets/24265534/56891d74-bb59-4e94-bfe0-009fb4a16c49)


This end-to-end ETL pipeline allowed me to efficiently process and visualize Olympic 2020 data on the Azure cloud platform. Each stage was crucial in ensuring the data was accurately represented in the final Power BI dashboard.
