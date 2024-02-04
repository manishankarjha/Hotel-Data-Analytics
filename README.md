# Hotel-Data-Analytics
Importing Excel file into SSMS then transferring it to Power BI to visualize data

## Introduction
We have been given Hotel data and asked to analyze Revenue Growth for each Hotel type from year 2018 to 2020, need to increase parking size, explore seasonality and find trends

## Tasks
- Created a Database & imported Excel data file in ``SQL Server Management Studio`` to populate this database
- Developed the SQL query using ``LEFT JOIN`` to combine tables & transfer data model to Power BI
- Connected Power BI to the database using above query in ``Advanced Options under Import Connection mode``
- Created New Columns & ``New Measures`` with the help of **DAX** queries in Power BI
- Visualize data and summarized findings altogether in a Dashboard

### Insights

- **Total Revenue** generated from both Hotel types is around ``$ 29 Million``.
- **Average Daily Rate** has been ``$ 104`` on average & slightly increased from 2018 to 2020.
- Average *Discount* has been ``26%`` & People spent fairly 3 to 4 nights in a Hotel booking.
- Months from ``July to October`` are a high time for Hotel Industries with maximum surge in **August**.
- Out of ``100K total bookings``, guests stayed for ``368K total nights`` & around ``8700 required car parking space`` which is 2% of total.
- As **BB**(Bed & Breakfast) is the cheapest meal, most customers``(~80 K)`` preferred it as an option.
  *(SC-Self Catering, HB-Half Board, FB-Full Board)*
- Maximum Bookings have been done through ``Online TA`` (~57%) and ``Offline TA/TO`` (~17%).
  *(TA-Travel Agents, TO-Tour Operators)*

***
### Recommendations

- The Hotel revenue is continuously increasing on yearly basis & management should focus build Customer satisfaction to increase repeats.
- There is no such need to increase the parking size as of now.
- Management should provide certain incentives for TA/TO with the maximum number of customers.
- Management also needs to ensure that online booking channels are reliable and available.

![Dashboard image-1](https://github.com/manishankarjha/Hotel-Data-Analytics/blob/main/Dashboard%20images/Hotel%20Analytics%20Dashboard_page-0001.jpg)
![Dashboard image-2](https://github.com/manishankarjha/Hotel-Data-Analytics/blob/main/Dashboard%20images/Hotel%20Analytics%20Dashboard_page-0002.jpg)
