# NASA Picture of the Day Web App

This web application fetches and displays NASA’s Astronomy Picture of the Day (APOD) using NASA’s open API.
Users can view the current image of the day, search for past dates, and save their search history — which persists in Local Storage.

# Technologies Used

HTML5
CSS3
JavaScript (ES6)
NASA APOD API
 
# Project Structure
NASA-Picture-of-the-Day/
│
├── index.html        # Main HTML structure
├── style.css         # Styling for the web page
└── script.js         # JavaScript logic

# How It Works

On page load, the app automatically calls the API and displays today’s image.
The user selects a date using the input field and clicks Search.
The app fetches and displays the image or video for that date.
The selected date is stored in Local Storage.
Previous searches are shown in a list below the form — clicking a date shows the image for that date again.

# API Reference
The API Endpoint to get information of a specific date looks like -  https://api.nasa.gov/planetary/apod?api_key=${your_api_key} 

# Clone this repository
git clone https://github.com/SurajKumar798/nasa-picture-of-the-day.git
