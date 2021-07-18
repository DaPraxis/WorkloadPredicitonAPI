# Historical Traffic APIs
## Listing
1. HERE API
    - Tutorial:
        + [Visualizing real-time traffic patterns using HERE traffic api](https://towardsdatascience.com/visualizing-real-time-traffic-patterns-using-here-traffic-api-5f61528d563)
    - [Official Web](https://developer.here.com/?cid=Freemium-Google-YT-0-Dev-Brand-E&utm_source=Google&utm_medium=ppc&utm_campaign=Dev_PaidSearch_DevPortal_AlwaysOn&utm_term=&gclid=Cj0KCQjw8vqGBhC_ARIsADMSd1AU0Uvc3slg7GeTV0qaVouAq18M3oZfEJ9FApLJBgcrH43E50uxPTsaAicGEALw_wcB&gclsrc=aw.ds):
        + [API docs](https://developer.here.com/develop/rest-apis) 
        + [Hazard Alert](https://developer.here.com/products/live-sense-sdk)
        + [Traffic Tile Map](https://developer.here.com/documentation/map-tile/dev_guide/topics/example-traffic.html)
        + [Traffic Tiles Info](https://developer.here.com/documentation/traffic/dev_guide/topics/tiles.html)
    - Third-party Interface:
        + [HerePy](https://herepy.abdullahselek.com/)
        + [Destination Weather](https://developer.here.com/documentation/examples/rest/auto_weather): Severe weather alert, weather forcast in 7 days, etc. works for **both Canada and China**
        + [Chinese Data](https://developer.here.com/documentation/routing-waypoints/dev_guide/topics/china-japan.html):
            Requires additional licensing and certifications to access (Chinese restrictions)
    - Comment:
        Traffic data not process-ready
2. Openroute service:
    - Tutorials:
        + [apartment search and nearby utilities](https://openrouteservice.org/example-apartment-search-with-ors/)
        + [Jupyter Examples](https://github.com/GIScience/openrouteservice-examples/)
    - [Official Web](https://openrouteservice.org/dev/#/home)
    - Third-party Interface:
        + [openrouteservice-py](https://github.com/GIScience/openrouteservice-py)
    - Comment: 
        No data on traffic, but more on geographical distances/optimizations and maps
3. TOMTOM:
   - IN PROGRESS!!!    
4. MapBox:
    - [Offical Web](https://www.mapbox.com/)
        + [API docs](https://docs.mapbox.com/)
        + Examples: playgrounds on API pages
    - Comment:
        Very similar to Openroute, but with better visualization, and worse pricing plan, not sure about free quota and data format yet, seems better format that Openroute

# Weather APIs
## Listing:
1. Government of **Canada**:
    - [Official Web](https://weather.gc.ca/)
    - Third Part Extractions:
        + [Forecast Feeds](https://github.com/jschnurr/ec-weather)
        + [env_canada](https://github.com/michaeldavie/env_canada)
    - [Weather Radar](https://weather.gc.ca/map_e.html?layers=radar&center=40.49730050%2C-94.79584784)
    - [Air Quality Health Index (AQHI)](https://weather.gc.ca/airquality/pages/index_e.html)
2. OpenWeatherAPIs (any locations):
    - [Project Source](https://github.com/CICCIOSGAMINO/openweather-apis)
    - [Demo](https://openweathermap.org/weathermap?basemap=map&cities=true&layer=temperature&lat=53.2258&lon=130.0781&zoom=3)
    - [API site](https://openweathermap.org/api)
