# Weather Forecast Report in Power BI

This project involved creating an interactive Power BI dashboard to visualize key weather metrics, 
including temperature, precipitation, and wind speed.

DATA:
1. Retrieved live data from Weather Data Query Page :: https://www.visualcrossing.com/weather/weather-data-services
2. Construct the Weather API query or download weather data using this page. To import live weather data into Power BI we need to copy the Weather API query.

Steps to make the data ready for the Weather API:
1. Create a free account on the Weather Data Query Page like other platforms.
2. Switch to the API view to generate the query URL. Using a query URL will allow us to directly import our live weather forecast data into Power BI.
3. Choose the weather forecast data for July 2024 to Jan 2025 for India.
4. This query will allow Power BI to fetch live data and refresh the data so that our forecast data is always current. Make sure you are logged into your account at this point so that ‘YOUR_API_KEY’ is replaced with your API key.
5. To switch to CSV format, change the format drop-down box. Finally, copy this URL into your clipboard.

After the weather data is retrieved, Follow the steps below for getting started with Microsoft Power BI :
1. Open Power BI and click on the "Get Data" button in the ribbon at the top of the screen. This will open the "Get Data" dialog box.
2. In the "Get Data" dialog box, we need to use a web data source to use weather data. Select "Web" from the list of data sources and click "Connect".
3. In the "Web" dialog box, enter the URL of the weather data API from above. Once you have entered the URL for the weather API.
4. Click "OK" to connect to the data. Power BI will import the data from the API.

Tools and Technologies:

• Power BI for building interactive dashboards and visualizing data

• DAX for performing advanced data analysis and calculations

Key Features:

• Visualizations of weather data such as temperature, precipitation, and wind speed.

Outcome:

The dashboard provided valuable insights into weather trends, facilitating improved decision-making and 

enhancing user engagement through interactive data exploration.
