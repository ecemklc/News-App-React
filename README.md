# News App

![news](https://github.com/user-attachments/assets/2b6221ac-5e75-44ae-9002-6dc5bcea66a6)


This application provides a platform to view news articles based on different categories. Users can browse news from various categories and filter news by country.

## Features

- Navigate through different news categories
- View top headlines for each category
- Filter news articles by country
- Responsive design with styled components

## Technologies Used

- React
- React Router DOM
- News API
- Styled Components

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-repo/news-app.git
    ```

2. Change to the project directory:

    ```sh
    cd news-app
    ```

3. Install the dependencies:

    ```sh
    npm install
    ```

4. Create a `.env` file in the root directory and add your News API key:

    ```
    REACT_APP_NEWS_API_KEY=your_news_api_key
    ```

5. Run the application:

    ```sh
    npm start
    ```

## Project Structure

src
├── components
│ ├── GlobalStyles.jsx
│ ├── Navbar.jsx
│ ├── NewsList.jsx
│ └── styled.js
├── pages
│ ├── Home.jsx
│ └── Category.jsx
├── App.jsx
└── index.js


## Components

### GlobalStyles.jsx
Defines global CSS styles using `styled-components`.

### Navbar.jsx
Provides navigation for different news categories.

### NewsList.jsx
Fetches and displays news articles based on the selected category.

### styled.js
Contains styled components used throughout the application.

## Pages

### Home.jsx
Displays news articles from the "general" category.

### Category.jsx
Displays news articles based on the selected category.


## API Key
To use the News API, replace your_news_api_key in the .env file with your actual News API key.
