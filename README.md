

<span>&#129311;</span> Cevi Herdian -> [itsmecevi.github.io](https://itsmecevi.github.io/) 

<span>&#128202;</span> About Tableau Software -> [Click Here](https://www.tableau.com/about)

<span>&#128201;</span> Technical Spesifications-> [Click Here](https://github.com/itsmecevi/Tableau-Technical-Specifications/blob/master/Tableau-Technical%20Specifications.pdf)

<span>&#xf108;</span> [Install Tableau free 14-day trial](https://www.tableau.com/en-gb/products/trial)

<span>&#xf108;</span> [Install Tableau Public Version](https://public.tableau.com/en-us/s/)

<span>&#xf108;</span> [Sign up Tableau Public account](https://public.tableau.com/s/)



## 1-Connecting to data

* Live connection :
     * When you have a fast database
     * When you need up-to-the minute data (real-time)
* Extract connection (in memory) :
     * When your database is too slow for interactive analytics
     * When you need to take load off a transactional database (size of the data)
     * When you need to be offline (without internet connections)
     
___________
* Excel : [World_Bank_CO2.xlsx](https://github.com/itsmecevi/world-bank-data/blob/master/World_Bank_CO2.xlsx)
* CSV : [FL_insurance_sample.csv](https://github.com/itsmecevi/FL_insurance_sample/blob/master/FL_insurance_sample.csv)
* PDF : [amazn_stock.pdf](https://public.tableau.com/s/sites/default/files/media/amzn_stock.pdf)
* Google Big Query: preparing your gmail account!


## 2-Data Preparation

* Data connections :
   * Union (vertical connection) : [amazn_stock.pdf](https://public.tableau.com/s/sites/default/files/media/amzn_stock.pdf)
   * Joins / Blend / Inner Join (horizontal connection) : 
   * Left Join, Right Join, Full Outer Join
* Data Interpreter & Data Pivoting (Unpivoting) : [CO2 API](https://github.com/itsmecevi/World-Data-CO2-API/blob/master/API_EN.ATM.CO2E.PC_DS2_en_excel_v2_247989.xls)
* Splitting : CO2 API Version-Indicator Name
* Manage data properties :
   * Rename a data field:
   * Assign an alias to a data value
   * Assign a geographic role to a data field
   * Change data type for a data field (number, date, string, boolean, etc.)
   
   
## 3-Understanding Tableau Concepts

Data: [Global-Superstore](https://github.com/itsmecevi/global-superstore-new/blob/master/Global%20Superstore.xls)

* Simple Tableau Workflow 
  * Workflow type 1 (we don't have data): outcome->design->data searching->Tableau
  * Workflow type 2 (we have data): data connection->data preparation->sheet->[dashboard]->story
* Show Me Tool Bar
* Dimensions and measures
* Column & Rows Shelf
* Marks Cards
* Discrete and Continuous Fields :
  * Blue color: discret, qualitative data (string, geographics, date, date & time, boolean). If added qualitative data, then they are      separate the graphs.
  * Green color: continuous, quantitative data, number, aggregation (sum, avg, etc).-> If added quantitative data, then they aren’t        separate the graphs.
* Hands-on chart: [Tableau Visual-> hands-on chart.twb + Data-> Global-Superstore](https://github.com/itsmecevi/hands-on-tableau)
  * 1-Word maps: country, profit
  * 2-Line chart: profit by category, profit by market, profit trendline, profit forecasting
  * 3-Bar chart: profit, profit by ship mode
  * 4-Bubble chart: profit by city
  * 5-Tree maps: profit by region and subcategory, profit clustering, profit by product
  * 6-Funnel chart: profit by segment
  * 7-Waterfall chart: profit by sub-category
  * 8-Pie chart: shipping cost by region
  * 9-Maps: profit by state
  
* Aggregation / Calculation: When to use calculations,
  * To segment data
  * To convert the data type of a field, such as converting a string to a date.
  * To aggregate data
  * To filter results
  * To calculate ratios
  * Hands-on calculation: [Calculation](https://github.com/itsmecevi/calculation-tableau)
  
        1. totals
        2. percentages
        3. profit ratio
        4. diskon ratio
        5. cost
        6. aov (average order value)
        7. profit status-if
        8. profit level-elseif
        
* Machine Learning: Quick Clusterisation & Forecasting
* Sheet
* Dashboard (Filter, Actions Highlight, & Formatting)
* Story



## 4-Executive Summary:

[Tableau from A-Z with data journalism](https://trello.com/c/7MSdbWmD/505-inovasi-dan-teknologi-baru-si-tableau)





