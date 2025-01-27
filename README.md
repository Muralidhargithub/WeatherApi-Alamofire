
# Weather API - Alamofire

A Swift project that demonstrates how to use the **Alamofire** library to fetch and display weather information from the [WeatherAPI.com](https://www.weatherapi.com/) API.

## Features

Fetch real-time weather data from WeatherAPI.com, parse JSON responses using Swift's `Codable` protocol, display weather information such as temperature, humidity, and conditions in a user-friendly UI, and implement best practices for network requests using Alamofire.

## Requirements

iOS 13.0 or later, Xcode 12 or later, Swift 5.0 or later.

## Installation

Clone the repository to your local machine using `git clone https://github.com/Muralidhargithub/WeatherApi-Alamofire.git`, navigate to the project directory using `cd WeatherApi-Alamofire`, open the project in Xcode using `open WeatherApi-Alamofire.xcodeproj`, and install dependencies using **Swift Package Manager (SPM)** by going to `File > Add Packages...` and adding the Alamofire package. Build and run the project by selecting a simulator or connected device in Xcode and clicking the Run button or pressing `Cmd + R`.

## Usage

Launch the app on your simulator or physical device, enter the desired city name or allow location access to retrieve weather data for your current location, and view the weather details, including current temperature, humidity level, and weather conditions.

## API Integration

This project uses the WeatherAPI.com API to fetch weather data. To integrate it, you need to sign up for an API key at [WeatherAPI.com](https://www.weatherapi.com/) and add your API key to the project. Locate the file `Constants.swift`, and replace the placeholder with your API key as follows:  
swift
let apiKey = "http://api.weatherapi.com/v1/forecast.json?key=43c47fcb7126427b9ad24119252701&q=21227&days=3&aqi=no&alerts=no"

##ScreenShot
<img width="317" alt="Screenshot 2025-01-27 at 2 07 00 AM" src="https://github.com/user-attachments/assets/e0b3a08c-ebd2-44d4-baf2-8fbd3b0388e2" />


## Dependencies

This project uses **[Alamofire](https://github.com/Alamofire/Alamofire)**, a powerful Swift HTTP networking library.

## Project Structure

The project includes `ViewControllers` for UI logic, a `Networking` layer for handling API requests using Alamofire, `Models` for defining data structures parsed from JSON using `Codable`, and `Utilities` for helper functions related to data formatting.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

Special thanks to [WeatherAPI.com](https://www.weatherapi.com/) for providing the weather data API and the developers of [Alamofire](https://github.com/Alamofire/Alamofire) for simplifying network requests in Swift.
```

This version includes everything in a single block so you can copy and paste it directly. Let me know if you need further adjustments!
