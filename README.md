# Currency Converter App

## Overview
The Currency Converter app is a React.js application that provides real-time currency exchange rates and allows users to convert amounts between different currencies. This app is designed to be user-friendly, accurate, and efficient, making it an essential tool for travelers, business professionals, and anyone dealing with multiple currencies.

## Features
- Real-time exchange rates for over 180 currencies.
- Currency conversion with instant results.
- Historical exchange rate data.
- Offline mode for saved exchange rates.
- Favorites for quick access to frequently used currencies.
- Built-in currency calculator.
- User-friendly interface with a clean layout.
- Multi-language support.
- Dark mode for reduced eye strain.
- Widgets for quick access to exchange rates.
- Notifications for specific exchange rate alerts.
- Secure and private.

## Technologies Used
- React.js
- Redux (for state management)
- Axios (for API requests)
- Styled-components (for styling)
- React Router (for navigation)
- Chart.js (for displaying historical data)
- Service Workers (for offline functionality)

## Installation
1. Clone the repository:
    ```bash
    https://github.com/ritikdevelop/Currency-Convertor-App.git
    cd currency-converter-app
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory and add your API key:
    ```plaintext
    REACT_APP_API_KEY=your_api_key_here
    ```

4. Start the development server:
    ```bash
    npm start
    ```

5. Open your browser and navigate to `http://localhost:3000` to view the app.

## Usage
1. **Home Page:** Displays the currency converter with real-time exchange rates. Select the currencies and enter the amount to convert.

2. **Historical Data:** View historical exchange rates for a selected date range. Analyze trends with interactive charts.

3. **Favorites:** Mark and access your most-used currencies quickly.

4. **Calculator:** Use the built-in calculator for complex currency conversions.

5. **Settings:** Customize language, theme (light/dark mode), and manage notifications for exchange rate alerts.

## API Integration
The app uses the [ExchangeRate-API](https://www.exchangerate-api.com/) to fetch real-time exchange rates. Ensure you have an API key from ExchangeRate-API and add it to the `.env` file.

## Contributing
1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Thanks to [ExchangeRate-API](https://www.exchangerate-api.com/) for providing the currency exchange rate data.
- Inspired by the need for a simple and efficient currency conversion tool.

---

**Download and start using the Currency Converter app today to simplify your currency conversion needs!**
