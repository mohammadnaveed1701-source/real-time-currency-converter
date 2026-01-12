# real-time-currency-converter
💱 Real-Time Currency Converter

A responsive Real-Time Currency Converter web application that converts amounts between multiple international currencies using live exchange rates.
This project demonstrates frontend development, asynchronous JavaScript, public API integration, and dynamic UI updates.

📌 Project Overview

The application allows users to convert currency values by selecting source and target currencies from dynamically populated dropdowns.
Exchange rates are fetched in real time from a public currency exchange API, and corresponding country flags update automatically based on currency selection.

This project is designed as a frontend portfolio project suitable for resumes, internships, and technical interviews.

🚀 Features

Real-time currency conversion
Supports multiple global currencies
Dynamic currency dropdown generation
Automatic country flag updates
Input validation for currency amount
Clean, responsive, and user-friendly UI
Default conversion on page load

🧠 How It Works

Currency dropdowns are populated dynamically using a currency–country mapping (codes.js)
When a currency selection changes, the country flag updates automatically
Exchange rates are fetched asynchronously from a public API using JavaScript fetch()
The converted value is calculated on the client side
Results are displayed instantly without page reload

🛠️ Tech Stack

HTML5 – Structure and layout
CSS3 – Styling and responsive design
JavaScript (ES6) – Logic, API handling, DOM manipulation
Font Awesome – Icons
Currency Exchange API – Live exchange rate data

🔌 API Usage

This project uses a public currency exchange API to retrieve real-time exchange rates.

Endpoint
GET https://api.exchangerate-api.com/v4/latest/{BASE_CURRENCY}

Example Request
GET https://api.exchangerate-api.com/v4/latest/USD

Sample Response
{
  "base": "USD",
  "rates": {
    "INR": 83.12,
    "EUR": 0.92,
    "JPY": 148.34
  }
}

API Integration Notes

Data is fetched asynchronously using fetch()
No backend server is required
Converted amount is calculated on the client side
API errors are handled gracefully

🌍 Supported Currencies

The application supports multiple international currencies using a predefined mapping of currency codes to country codes.
This enables:
Dynamic dropdown generation
Automatic country flag rendering

Examples

USD → US
INR → IN
EUR → FR
JPY → JP

📂 Project Structure
currency-converter/
│── index.html
│── style.css
│── app.js
│── codes.js

🎯 Purpose

This project was built for learning and portfolio demonstration, showcasing:
Real-world API integration
Asynchronous JavaScript usage
Dynamic UI updates
Clean and responsive frontend design
Practical problem-solving skills

📌 Project Status

✔ Completed
✔ Actively maintained for learning improvements

📄 License
This project is open-source and available for educational and personal use.
