<h1 align="center"><b>Weather App</b></h1>

<h1 align="center"><b>
  
![weatherReact](https://github.com/thebarunkumar/Weather-App/assets/77458180/f810e6c9-85ad-4216-8ae7-79943117bcac)
    
</b></h1>

The objective of this project is to develop a web application that utilizes the Open Weather Map API to present weather forecasts. Users can search for specific locations worldwide. Additionally, the application will automatically determine the user's current location (with location permission) and display comprehensive weather information.

The application boasts several notable features. It stores weather data efficiently using redux-store and session-storage to minimize reliance on network requests. Users can search for weather details by city, view a map of selected locations, and receive the most up-to-date weather updates through data synchronization. The app provides toast notifications for each action, pop-up modals for detailed seven-day forecast information, appealing zoom-in and zoom-out animations, and is designed to be responsive across various screen sizes.

To utilize the app, simply enter a city name and click "search" or press "Enter". Alternatively, click the "Your location weather" button. Each time the button is pressed, the app checks session storage for available data. If not found, it initiates a network request to retrieve the data; otherwise, it fetches the data from session-storage.

Features:
- Efficiently storing weather data using redux-store and session-storage to minimize network requests
- City-based weather details search
- Automatic detection of the user's current location for displaying weather data
- Display of location maps
- Synchronization of data to provide the latest weather updates
- Toast notifications for every user action
- Pop-up modals offering additional details for a seven-day forecast
- Engaging zoom-in and zoom-out animations
- Responsiveness across diverse screen sizes.
