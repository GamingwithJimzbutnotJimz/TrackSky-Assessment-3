# TrackSky-Assessment-3
Tracksky is a weather temperature forecast IOS application developed with SwiftUI. It is designed to showcase advanced IOS developement conepts that are utilised to create a functional app. The application demonstrates user CoreData, UserDefaults, CoreLocation, MapKit, and REST API integration to deliver a forecasting app in the modern-wolrd. The weather API that has been utilised was attained from weatherapi.com.

This project efficiently outlines the criteria provided for Assessment 3 of Advanced IOS Development, which invldes local and cloud based user data management, networking, JSON parsing, UI, error handling and testing.

# **Setup Instruction**
To develop this IOS applicaton, the following apporach was taken in order to setup the correct XCode Environment:

**Pre-requisites:**

- When creating project make sure to select CloudKit

- Ensure the account is signed into the ICloud in order to enable CoreData and CloudKit features. This can be found in Signing and Capabilities
  

**API Key Setup**

- Navigate to "Secrets.swift".
  
- Insert API key into "weatherAPIKey".

**Run the Project**

- Select an IOS Simulator.
  
- Press Run.
  
- Select a Location Access option in the launch of the APP.


**Features**
The features that are inclded for a satisfactory user experience is as follows:

- Current Weather:
    - Provides a display for live weather in the user's current location using CoreLocation and WeatherAPI.
      
- Hourly Forecast:
    - By implementing SWIFT Charts, a graph is provided for hourly temperature trends that are recorded.
      
    - A scroll-wheel that displays the hourly temperatures of the current locations weather.

- Favourite Location:
  
    - Users can save, view, and delete locations that are added to the favourite list.
 
- Search By City:

    - A view that provides users to search for cities by name.
      
    - Add the searches cities directly to the favourite list.
 
- Map:

    - Through the integration of MapKit, users can view the map of the current city that is being observed for the weather forecast. 

- Unit Switching:
  
    - Users can toogle metrics between Celcius and Fahrenheit.
    
    - The choice is stored through UserDefaults.
- Error Handling:
  
    - A banned will display indicating to users the location is missing, API failures, or saved errors.

# **User Guide:**

For users to precisely navigate throughout the application the following guide can be followed:

1. Launch the application - an option will be provided to users to choose a specific location tracking preference.
   
2. Save Location  - add current location/searched cities to the favourites list.

3. Search Cities - search for cities that users desire for.

4. Click Favourited Location - view a detailed forecast description, hourly chart and map of the selected city

5. Switch metric - use the toggle option in the top of the front page to select the metric of temperature.

6. Delete Favourited Location - click the trash icon to delete desired favourite locationm.

By following this guide users are provided with a detailed weather application for temperature tracking.

# **Error Handling**

To ensure users are provided indication for incorrect inputs, or missing data in the application, the following error handling technqieus are used:

- No Location - if the current location is not identified by the application a banner stating "No Location" appears on the page.

- Save Failure - banner "Save Failed" is provided if the location cannot be saved by the user

- Search Failure - in te search view, if the location is not found, "No Results" is displayed.

# **Conclusion**

The application that is developed for this task demonstrates a modern IOS weather app, that tracks the temperature of the user's current location and locations that user's would like to search for. Through implementing SwiftUI methods stated in the criteria of this task, a satisfactory applicationm has been produced.


 
 




  
