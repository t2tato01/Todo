# Oulu University of Applied Sciences Android Walkthrough

## Overview

This walkthrough guides you through the process of creating a Todo app in Android, focusing on creating a ViewModel to manage the data. The walkthrough is divided into three parts:

1. **Creating Basic Todo App**: In this part, we'll create a simple Todo app with hardcoded values displayed in a list, managed by a ViewModel class.

2. **Connecting to the Internet and Fetching JSON Data**: Here, we'll enhance the app by connecting it to the internet, fetching JSON data using Retrofit and Gson libraries. We'll also establish the MVVM architecture for the app.

3. **Handling Errors and Loading Messages**: The final part focuses on error handling and displaying loading messages while data is being retrieved from the API service.

## Part 1: Creating Basic Todo App

In this part, we'll create the foundation of the Todo app. We'll start with hardcoded values displayed in a list managed by a ViewModel class.

## Part 2: Connecting to the Internet and Fetching JSON Data

This part enhances the Todo app by adding connectivity to the internet. We'll use Retrofit and Gson libraries to fetch JSON data from an API and implement the MVVM architecture for better code organization.

## Part 3: Handling Errors and Loading Messages

In the final part, we'll focus on error handling and improving the user experience by displaying loading messages while data is being retrieved from the API service.

## Project Structure

The project follows standard Android architecture principles and is organized into packages:

- **ui**: Contains the MainActivity and UI-related components.
- **model**: Includes data models used in the application.
- **viewmodel**: Contains the ViewModel class responsible for managing data and UI logic.

## Libraries Used

- **Retrofit**: A type-safe HTTP client for Android and Java.
- **Gson**: A Java library for serializing and deserializing JSON objects.
- **ViewModel**: Part of the Android Architecture Components, ViewModel is responsible for managing UI-related data.

## Getting Started

To begin, create a new Android project using an Empty Compose Activity template. Add the ViewModel library to the `build.gradle` file and sync the project. Follow the provided walkthrough instructions for each part to complete the Todo app.

