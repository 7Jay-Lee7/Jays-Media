# Jays Media
Jays Media is a YouTube clone app built with React that allows users to browse, search, and watch videos.

## Installation
To install Jays Media, follow these steps:

1. Clone the repository: git clone https://github.com/7Jay-Lee7/jays-media.git
2. Navigate to the project directory: cd jays-media
3. Install the dependencies: npm install
4. Head to [Rapid API](https://rapidapi.com/ytdlfree/api/youtube-v31?utm_source=youtube.com%2FJavaScriptMastery&utm_medium=referral&utm_campaign=DevRel%2F) and you want to click on GET Suggested Video and on the right-hand side, there will be some Json and you want to get yout API-KEY from 'X-RapidAPI-Key': line. 
5. Create a .env file in the project root directory with the following environment variables:
6. REACT_APP_RAPID_API_KEY=<your_rapid_api_key>

## Usage
To start the app, run the following command:
npm start
This will start the app and open it in your default browser at http://localhost:3000.

## Features
Jays Media currently supports the following features:

1. Search for videos using the YouTube Data API v3
2. View a list of search results with video thumbnails, titles, and channel information
3. Click on a video to watch it in a video player
4. Browse recommended videos on the video player page
5. Use the responsive design on different screen sizes

## Technologies Used
Jays Media was built with the following technologies:

React
React Router
Axios
YouTube Data API v3 via [Rapid API](https://rapidapi.com/ytdlfree/api/youtube-v31?utm_source=youtube.com%2FJavaScriptMastery&utm_medium=referral&utm_campaign=DevRel%2F)

## Contributing
Contributions to Jays Media are welcome! To contribute, follow these steps:

## Fork the project
Create a feature branch: git checkout -b feature/new-feature
Make your changes and commit them: git commit -am 'Add new feature'
Push to the branch: git push origin feature/new-feature
Submit a pull request

## License
Jays Media is licensed under the MIT license. See LICENSE for details.
