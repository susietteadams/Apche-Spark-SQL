![image](https://user-images.githubusercontent.com/43391446/68617459-58857180-0495-11ea-8794-4143c75488ee.png)

Apche-Spark-SQL
Used Cars Analysis

Introduction

To enter into this new market we had our data scientist analyse data that was collected in Germany, and Czech Republic since 2015. We plan to invest in dealerships within Eastern Europe. Some of the sources provided unstructured data, so as a result the data is dirty. There are missing values and some values are very wrong. For example phone numbers have been inputted as mileage in some cases. The data is consist of roughly 3.5 Million rows and sixteen columns: maker, model, mileage - in KM, manufacture_year, engine_displacement, engine_power, body_type, color_slug, stk_year, transmission, door_count, seat_count, fuel_type, date_created, date_last_seen, price_eur. The data scientist used Zeppelin a derivative of Apache Spark SQL, to analyse the data.

Loading the data.

![image](https://user-images.githubusercontent.com/43391446/68617620-a4d0b180-0495-11ea-8543-5112de9a0293.png)

The top car makers with resale values.

![image](https://user-images.githubusercontent.com/43391446/68617749-e3666c00-0495-11ea-8ff9-3f62f99f04c0.png)
