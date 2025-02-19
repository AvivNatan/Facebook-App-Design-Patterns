# Desktop Facebook Application

## Overview

This is a desktop Facebook application built with C# and the Facebook Graph API. The app provides enhanced user interaction with Facebook data through a Windows Forms interface. It features a user-friendly design pattern architecture that makes the code maintainable, extensible, and organized.

## Features

### Core Features
- **User Authentication**: Log in to your Facebook account securely
- **Profile View**: Display user profile information and profile picture
- **Posts Browser**: Browse through your Facebook posts
- **Pages Browser**: View pages you follow with thumbnail images
- **Groups Browser**: Access your Facebook groups
- **Albums Browser**: Navigate through your photo albums with preview capabilities

### Unique Features

#### 1. Guess The Moment Game
A fun interactive game that:
- Randomly selects a photo from your albums
- Challenges you to guess when the photo was taken
- Provides feedback on your guess accuracy
- Makes browsing through memories more engaging

#### 2. Album Downloader
Utility that allows you to:
- Browse through your Facebook albums
- Preview album contents before downloading
- Select a custom destination folder on your computer
- Download entire albums with sorting options:
  - Sort by creation time (ascending/descending)
  - Sort by comments amount (ascending/descending)

## Architecture

The application implements several design patterns to ensure clean, maintainable code:

### Design Patterns
1. **Proxy Pattern**: Implements caching for Facebook data to improve performance and reduce API calls
2. **Factory Method**: Manages form creation throughout the application
3. **Singleton**: Ensures single instance management for game state
4. **Strategy Pattern**: Provides flexible album sorting mechanisms
5. **Observer Pattern**: Maintains synchronization between UI components and login state
6. **Iterator Pattern**: Enables clean traversal of post collections

### Technical Implementation
- **Asynchronous Programming**: Implemented throughout for responsive UI
- **Data Binding**: Used for efficient UI updates when data changes
- **Thread Management**: Ensures smooth performance during data-intensive operations

## Requirements
- .NET Framework 4.5 or higher
- Valid Facebook developer credentials
- Internet connection for Facebook API access

## Getting Started
1. Clone the repository
2. Open the solution in Visual Studio
3. Configure your Facebook App ID in the settings
4. Build and run the application

## Contributors
This project was developed as part of an academic course on Design Patterns and Object-Oriented Programming.
