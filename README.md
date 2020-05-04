# Covid-19-Tracker-US-
Power-BI Dashboard tracking and analyzing Covid-19 cases and deaths in the United States.


For interactive public use online please visit the following link below: 
https://app.powerbi.com/viewr=eyJrIjoiODcwMjlkZWUtYzY4YS00Y2IwLWI1YzYtMTlkOGNlYzlmYTEwIiwidCI6ImY4MTcyNWVhLTE4MDctNGIzNC1hMTliLTkwNjM0YTMzYjE4ZSIsImMiOjZ9


Data Sources:
  1. John Hopkins University - https://github.com/CSSEGISandData
  2. NewsAPI - https://newsapi.org/
  3. The Covid Tracking Project - https://covidtracking.com/api
  4. United States Census Bureau - https://www.census.gov/data/developers/data-sets/popest-popproj/popest.html
  

Map Creation:
  1.County & State Boundary lines where downloaded (JSON Files) - Multiple sources to download from online.
  2.They were then converted in shape map to geojson files.
  3.The geojson was then uploaded to mapbox to create tilesets.
  4. Once the mapbox tileset is created you then download the mapbox app within power bi and paste the custom mapbox url genereated from        your tileset in mapbox site.
  5. This then generates the map in Power-BI with county and state lines.
  
  
 All other visuals used are free within Power-BI marketplace.
 UI/UX is original content, no template created...yet
 
For data cleansing from sources, all applied steps listed within power query editor. Once you open the pbix you can go to "Transform Data" tab to view all tables and applied steps.
Data is not pulled from dataflows, it is pulling straight from sources.
