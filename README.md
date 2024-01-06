# Bitcoin Price Checker

> **Note:** The description below and the code in this repo are created using Copilot by Microsoft.

This repository contains a static web page that checks and displays the current price of Bitcoin in USD.

## Project Overview

The project uses the Axios library to make HTTP requests to the Coinbase API, which provides real-time Bitcoin prices. The web page updates every 30 seconds to display the latest price.

## Code Explanation

The code is written in HTML and JavaScript. It uses the Axios library to make HTTP requests to the Coinbase API. The API endpoint used is 'https://api.coinbase.com/v2/prices/BTC-USD/buy', which returns the current buying price of Bitcoin in USD.

An asynchronous JavaScript function, `getBitcoinPrice()`, is defined to make the API request and update the web page with the latest price. This function is called immediately when the page loads, and then every 30 seconds using the `setInterval()` function.

## How to Use

To use this project:

1. Clone the repository to your local machine.
2. Open the HTML file in a web browser.

> **Note:** This project is for informational purposes only and should not be used as financial advice.

## Contributing

Contributions to improve the code or add new features are welcome. Please read the CONTRIBUTING.md file for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License. See the LICENSE.md file for details.
