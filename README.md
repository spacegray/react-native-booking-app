# Booking App
## Using React Native
This is a mobile app that allows users to browse and book accommodations based on their preferred location and date range. Users can also view their bookings, view saved places, and manage their profile. This app is built with Expo and integrates Firebase for authentication and data storage.

## Features
* Comprehensive search with filters for destination, date, and travelers
* Map screen to visualize the locations of accommodations
* User profiles for managing bookings and saved places
* View room details, photos and amenities
* Secure authentication and data storage using Firebase

## Getting Started
To get started with this app, follow these steps:

Clone this repository to your local machine using git clone.

Install the necessary dependencies by running npm install in the project directory.

**Requires an ios or Android Simulator**

For full functionality, Create a Firebase project and configure it with your preferred authentication and data storage options.

In the project directory, create a new file called firebase.js and add your Firebase configuration information, like so:

```javascript
Copy code
import firebase from 'firebase';

const firebaseConfig = {
  // Add your Firebase configuration information here
};

firebase.initializeApp(firebaseConfig);

export default firebase;
```
Start the app using `expo start`
