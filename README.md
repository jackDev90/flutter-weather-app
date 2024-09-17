Flutter Weather App

A simple Flutter application that fetches and displays weather data using an API. This app demonstrates how to make API calls and present weather information in a user-friendly interface.
Table of Contents

    Setup Instructions
    Libraries Used
    Running the App

Setup Instructions

    Clone the Repository

git clone https://github.com/jackDev90/flutter-weather-app.git
cd flutter-weather-app

Install Flutter

Ensure you have Flutter installed on your machine. Follow the official Flutter installation guide if needed.

Install Dependencies

Run the following command to fetch the necessary Dart packages:


flutter pub get

Configure API Keys

        WEATHER_API_KEY=your_api_key_here

    Ensure you replace your_api_key_here with your actual API key from your chosen weather API provider.

Libraries Used
    http: For making HTTP requests.

Add these dependencies to your pubspec.yaml file:

yaml

dependencies:
  flutter:
    sdk: flutter
  http: ^1.2.2


Running the App

    Run the App

    Use the following command to run the app on your emulator or connected device:


flutter run

Build and Release

For building a release version of the app, use:


flutter build apk

or


flutter build ios

depending on your target platform.