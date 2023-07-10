## Week 4: Networking and APIs
### Day 1, 2 & 3:
1. Understand how to make API requests and handle responses in Flutter.
2. Use packages like HTTP or Dio to fetch data from REST APIs.
3. Learn about HTTP packages
4. Learn about JSON parsing

### Day 4, 5 & 6:
1. Weather app that fetches data from a weather API and displays the current weather conditions for a given location
   * Here's a step-by-step guide to help you get started:
      * Choose a weather API: There are several weather APIs available, such as OpenWeatherMap, Weatherbit, or AccuWeather. Select one that suits your needs and sign up for an API key.
      * Set up a new Flutter project: Open your favorite Flutter IDE, create a new Flutter project, and set up the necessary dependencies.
      * Design the user interface: Decide how you want to present the weather information to the user. Create a visually appealing layout with widgets like Text, Image, and Icon.
      * Fetch weather data from the API: Use the HTTP package in Flutter to make API requests. Construct the URL using your API key and the desired location, and send a GET request to retrieve the weather data.
      * Parse the JSON response: Once you receive the response from the API, parse the JSON data using the Dart convert package. Extract the relevant weather information, such as temperature, humidity, and weather conditions.
      * Update the UI with the fetched data: Update the UI widgets with the weather information obtained from the API. For example, display the current temperature, weather icon, and a brief description of the weather conditions.
      * Handle error cases: Implement error handling to account for situations where the API request fails or returns invalid data. Display appropriate error messages or fallback content to the user.
      * Add extra features: To enhance the app, you can include additional features like a search bar to enter a specific location, a five-day forecast, or the ability to save favorite locations.
      * Test and debug: Thoroughly test your app on different devices and screen sizes to ensure it works correctly. Debug any issues that arise during the testing process.
