
---

# NewsApp

NewsApp is a dynamic web application that fetches and displays the latest news articles using the News API. The app is built with React and includes features like navigation through a Home and About Us page, paginated news articles with Previous and Next buttons, and it displays live and real news and events going around the world.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contact](#contact)

## Features

- **Home Page:** Displays the latest news articles fetched from the News API.
- **About Us Page:** Provides information about the app.
- **Navigation Bar:** Easy navigation between Home and About Us pages.
- **Pagination:** Navigate through news articles using Previous and Next buttons.
- **Responsive Design:** Ensures a seamless experience across different devices.

## Technologies Used

- **Frontend:** React, HTML, CSS
- **API:** News API

## Setup and Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/ronaksharma77/NewsApp.git
    cd NewsApp
    ```

2. **Install dependencies:**
    ```sh
    npm install
    ```

3. **Set up environment variables:**
    Create a `.env` file in the root directory and add your News API key:
    ```env
    REACT_APP_NEWS_API_KEY=your_news_api_key
    ```

4. **Run the application:**
    ```sh
    npm start
    ```

    The application will be served on `http://localhost:3000`.

## Usage

- **Home Page:**
  - Displays the latest news articles.
  - Use the Previous and Next buttons at the bottom to navigate through the pages of articles.

- **About Us Page:**
  - Provides information about the NewsApp and its features. It is left empty as of now.

## Project Structure

```
NewsApp/
│
├── public/                # Public assets
│   ├── index.html         # Main HTML file
│   └── ...                # Other public files
│
├── src/                   # Source code
│   ├── components/        # React components
│   │   ├── Navbar.js      # Navigation bar component
│   │   ├── News.js    # Component to display news articles
│   │   └── ...            # Other components
│   │
│   ├── pages/             # Page components
│   │   ├── Home.js        # Home page component
│   │   └── About.js       # About Us page component
│   │
│   ├── App.js             # Main App component
│   ├── index.js           # Entry point for the frontend
│   └── ...                # Other source files
│
└── README.md              # This README file
```

## Contact

For any inquiries or feedback, please reach out to:

- **Name:** Ronak Sharma
- **Email:** ronaksharma.rk77@gmail.com
- **GitHub:** [ronaksharma77](https://github.com/ronaksharma77)
