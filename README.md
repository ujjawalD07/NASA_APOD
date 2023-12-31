# NASA APOD React App

## Overview

Welcome to the NASA APOD (Astronomy Picture of the Day) React App! This application allows users to explore and view the captivating images and information provided by NASA's Astronomy Picture of the Day API. Users can discover a new astronomy-related image each day, along with its description and additional details.

## Features

- **Daily Image:** Display the Astronomy Picture of the Day along with its title, date, and a brief explanation.
- **Random Image:** Explore a random astronomy image and its details.
- **Responsive Design:** The app is designed to work seamlessly on various screen sizes, including desktops, tablets, and mobile devices.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/NASA_APOD.git
   ```

2. Change into the project directory:

   ```bash
   cd NASA_APOD
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the project root and add your NASA APOD API key:

   ```env
   REACT_APP_NASA_APOD_API_KEY=your-api-key
   ```

   You can obtain an API key by signing up at [NASA API Key Signup](https://api.nasa.gov/).

5. Start the development server:

   ```bash
   npm start
   ```

   The application will be accessible at `http://localhost:3000` by default.

## Configuration

You can customize the application by modifying the `config.js` file. Update the `defaultDate` to set the default date when the app loads, and adjust other configuration options as needed.

## Technologies Used

- React: A JavaScript library for building user interfaces.
- Axios: A promise-based HTTP client for making API requests.
- NASA APOD API: Provides access to NASA's Astronomy Picture of the Day.

## Contributions

Contributions are welcome! If you have ideas for improvements or new features, feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Enjoy exploring the wonders of the universe with the NASA APOD React App! If you have any questions or feedback, please don't hesitate to reach out.

**Happy stargazing!** 🌌🚀
