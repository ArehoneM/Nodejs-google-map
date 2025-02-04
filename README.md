# Nodejs-google-map

This is a Node.js application that integrates Google Maps with address autocomplete functionality.

## Features:

- Interactable Google Map: Users can search for or click on any location.

- Address Autocomplete: Uses Google Places API for auto-suggestions.

- Pin Drop & Info Window: When a location is searched or clicked, a pin is placed, and details appear in an info window.

- Click-to-Get-Info: Clicking anywhere on the map fetches and displays details of that location.

## Installation & Setup:

1. Prerequisites:

  - Node.js installed on your system ([Download Here](https://nodejs.org/en))

  - Google Maps API Key ([Get API Key](https://console.cloud.google.com))

2️. Clone the Repository

   - git clone [https://github.com/ArehoneM/Nodejs-google-map.git](https://github.com/ArehoneM/Nodejs-google-map.git)
   - cd Nodejs-google-map

3️ Install Dependencies:

  - npm install

4️ Setup Environment Variables

  - Create a .env file in the root directory and add:
     **Renders as:*
    ```sh

    PORT=3000
    GOOGLE_MAPS_API_KEY=your_google_maps_api_key ```  

   - Replace your_google_maps_api_key with your actual API key.

5️ Run the Application:

 - node server.js

6️ Open in Browser:

Go to: [http://localhost:3000](http://localhost:3000)





