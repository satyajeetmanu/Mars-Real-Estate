##Introduction

The "Mars Real Estate" project is a simple demo app using ViewModel & LiveData with Retrofit, Glide and Moshi in Kotlin. This app demonstrates the following views and techniques:
Retrofit to make API calls to an HTTP web service
Moshi which handles the deserialization of the returned JSON to Kotlin data objects
Glide to load and cache images by URL
It leverages the following components from the Jetpack library:
ViewModel
LiveData
Data Binding with binding adapters
Navigation with the SafeArgs plugin for parameter passing between fragments


##Features

Display a list of available real estate on Mars
Filter real estate by type (e.g. rent, buy)
Navigate to detailed information about a specific real estate listing
Getting Started
Prerequisites
To run this project, you'll need to have the following installed on your system:
Android Studio
Kotlin


##Installation

Clone the repository:
bash
git clone https://github.com/satyajeetmanu/Mars-Real-Estate.git

Open the project in Android Studio.
Build and run the app on an emulator or physical device.


##Usage


Viewing Mars Real Estate
When you launch the app, you'll see a list of available real estate listings on Mars. Each listing displays the type of property (e.g. rent, buy) and the price.
Filtering Real Estate
You can filter the real estate listings by type (rent or buy) using the buttons at the top of the screen.
Navigating to Details
To view more details about a specific real estate listing, tap on the listing in the list. This will navigate you to a new screen with additional information about the property.
