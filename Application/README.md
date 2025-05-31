# Mobile Application

This directory contains the Flutter-based mobile application for Fake News Detection.

## Overview

The application provides a user-friendly interface for detecting fake news by:

1. Allowing users to input news articles (title, content, source URL)
2. Sending the input to the Flask API for analysis
3. Displaying comprehensive results about the credibility of the news

## Structure

The application is contained in the `fake_news_detectio_system` directory which is a standard Flutter project with:

- `lib/`: Contains the Dart source code
- `android/`: Android-specific configuration
- `ios/`: iOS-specific configuration (if available)
- `pubspec.yaml`: Flutter dependencies

## Running the Application

1. Ensure you have Flutter SDK installed
2. Open the project in Android Studio or VS Code
3. Start an Android emulator
4. Run port forwarding to allow communication with the API:
   ```
   adb reverse tcp:5000 tcp:5000
   ```
5. Run the application from your IDE or using Flutter CLI:
   ```
   flutter run
   ```

## Development

The application communicates with the Flask API using HTTP requests and displays the results in a user-friendly format.

For any modifications:
1. Ensure the API endpoints match those in the backend implementation
2. Test thoroughly with various news inputs
3. Update UI elements as needed

## Dependencies

All Flutter dependencies are managed in the `pubspec.yaml` file within the `fake_news_detectio_system` directory.
