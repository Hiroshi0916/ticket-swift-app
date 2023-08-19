# Event Ticket Search App

[![Watch the video](https://img.youtube.com/vi/_jiXbs9d8MQ/0.jpg)](https://youtu.be/_jiXbs9d8MQ)
### You can check the app's functionality by clicking on the image
#### This is an academic project, so the code is not publicly available. If requested during the hiring process, I will grant access permissions
## Overview

A comprehensive app that allows users to search for event details, view them, and engage with various functionalities.

## Features and Characteristics

### **Search Form**
- **Autocomplete**: Autocomplete function for keyword input. Comes with a debouncer to minimize unnecessary API calls.
- **Categories**: Dropdown selection available for different event categories.
- **Location Preferences**: Features fields for specifying distance and location, with an auto-detection toggle.
- **Buttons**: Submit and clear buttons incorporated with validations (like empty keyword or location checks).

### **Search Results**
- Displays results in a list format after successful validation.
- Each item shows the category image, event name, venue name, and event date-time.

### **Event Details**
- **Tabs**: Divided into multiple tabs to show event information, artist/team details, and venue details.
- **Save and Share**: Users can save events to their favorites or remove them. There's also a sharing function for Twitter and Facebook.

### **Artist Tab**
- Displays artist details, popularity metrics, links to Spotify, and top albums.
- For non-music events, there's a message indicating unavailable artist/music data.

### **Venue Tab**
- Shows detailed information about the venue including its name, address, phone number, operational hours, and general rules.
- Comes with an option to view the venue on Apple Maps.

### **Favorites List**
- Switch between the search and favorites views.
- List favorite events without a favorite button. Options include viewing event details or removing an event from favorites.

## Technical Aspects

### **Development Environment: Xcode**
- Xcode is the integrated development environment (IDE) tailored for Apple platforms.
- The app's codebase is in Swift.
- Adheres to the Model-View-Controller design pattern, ensuring a clear distinction between the app's data, logic, and presentation layers.

### **Development Language**: Swift

### **UI Framework**: SwiftUI

### **Icon Library**: SF Symbols

### **Development Tool**: Xcode

### **Backend**: Node.js script
- Hosted on the GCP platform.

