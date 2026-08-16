<div align="center">

# 💱 Real-Time Currency Converter

### Live Exchange Rates • REST API Integration • Responsive Design

*A modern currency conversion web application built with **HTML5**, **CSS3**, and **JavaScript**, providing real-time currency conversion through external API integration with a clean and responsive user interface.*

<br>

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Website-00C853?style=for-the-badge)](https://real-time-currency-converter170.vercel.app/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![REST API](https://img.shields.io/badge/REST_API-Integrated-success?style=for-the-badge)](#)
[![Responsive](https://img.shields.io/badge/Responsive-Yes-success?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Completed-blue?style=for-the-badge)](#)

</div>

---

# 📑 Table of Contents

- [📖 Overview](#-overview)
- [🎯 Project Goals](#-project-goals)
- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [🏗️ Application Workflow](#️-application-workflow)
- [⚙️ Core Functionalities](#️-core-functionalities)
- [📂 Project Structure](#-project-structure)
- [🌍 Supported Currencies](#-supported-currencies)
- [💡 Skills Demonstrated](#-skills-demonstrated)
- [🎯 Learning Outcomes](#-learning-outcomes)
- [⚡ Performance](#-performance)
- [🌐 Browser Support](#-browser-support)
- [🚀 Future Enhancements](#-future-enhancements)
- [📈 Project Highlights](#-project-highlights)
- [⚠️ Disclaimer](#️-disclaimer)
- [👨‍💻 Developer](#-developer)
- [🤝 Contributing](#-contributing)
- [⭐ Support](#-support)

---

# 📖 Overview

**Real-Time Currency Converter** is a modern frontend web application that allows users to convert amounts between multiple international currencies using live exchange rate data from an external API.

Built with **HTML5**, **CSS3**, and **JavaScript**, the application combines API integration, asynchronous programming, dynamic DOM manipulation, and responsive web design to create an interactive currency conversion experience.

Users can select a source currency, choose a destination currency, enter an amount, and receive the converted value based on the latest available exchange rate returned by the integrated API.

The project was developed as a practical exercise in building **data-driven frontend applications** and working with external services through JavaScript.

---

# 🎯 Project Goals

The primary goals of this project were to:

- Build a real-world API-driven frontend application.
- Practice asynchronous JavaScript.
- Learn how to consume REST APIs.
- Work with JSON responses.
- Implement dynamic DOM updates.
- Build responsive user interfaces.
- Handle user input and API errors.
- Strengthen practical JavaScript skills.
- Create a portfolio-ready application.

---

# ✨ Features

## 💱 Real-Time Currency Conversion

- Retrieve current exchange rate data.
- Convert amounts between supported currencies.
- Perform calculations dynamically.
- Display conversion results instantly.

---

## 🌍 Multi-Currency Support

- Support for numerous international currencies.
- Dynamic currency selection.
- Currency-to-country mapping.
- Easy switching between source and target currencies.

---

## 🚩 Dynamic Country Flags

- Automatically update flags based on selected currencies.
- Map currencies to their corresponding country codes.
- Improve currency identification through visual feedback.

---

## 🔄 Currency Swap

- Swap source and destination currencies with one click.
- Automatically update the selected currencies.
- Recalculate the conversion after swapping.

---

## ⚡ External API Integration

- Retrieve live exchange rate information.
- Process API responses dynamically.
- Parse JSON data.
- Handle asynchronous requests using JavaScript.

---

## ⚠️ Error Handling

The application is designed to handle common situations such as:

- Empty amount fields.
- Invalid user input.
- API request failures.
- Network-related issues.
- Unexpected API responses.

---

## 📱 Responsive Design

The interface is designed to provide a consistent experience across:

- 💻 Desktop
- 🖥️ Laptop
- 📱 Tablet
- 📲 Mobile Devices

---

## 🎨 Modern User Interface

- Clean and intuitive layout.
- Gradient-based visual design.
- Interactive controls.
- Responsive components.
- Clear conversion results.
- User-friendly currency selection.

---

# 🛠️ Tech Stack

## Frontend

- HTML5
- CSS3
- JavaScript (ES6)

---

## APIs & Services

- Exchange Rate API
- Country Flags API

---

## JavaScript Concepts

- Fetch API
- Promises
- Asynchronous Programming
- DOM Manipulation
- Event Handling
- JSON Parsing
- Dynamic Rendering
- Error Handling

---

## Development Tools

- Visual Studio Code
- Git
- GitHub
- Vercel

---

# 🏗️ Application Workflow

```text
              User
                │
                ▼
        Enter Amount
                │
                ▼
       Select Base Currency
                │
                ▼
      Select Target Currency
                │
                ▼
        Request Exchange Rate
                │
                ▼
          External API
                │
                ▼
         Receive JSON Data
                │
                ▼
       Process Exchange Rate
                │
                ▼
       Calculate Conversion
                │
                ▼
     Update Currency & Flags
                │
                ▼
        Display Final Result
```

---

# ⚙️ Core Functionalities

## 🌐 Exchange Rate Retrieval

The application sends a request to an external exchange rate service and processes the returned data to obtain the required currency conversion rate.

---

## 💱 Dynamic Currency Selection

Currency options are populated dynamically, allowing users to select their desired source and destination currencies.

---

## 🔄 Currency Swap

The swap functionality allows users to quickly exchange the selected source and destination currencies without manually selecting them again.

---

## 🚩 Dynamic Flag Rendering

The application updates country flags according to the selected currencies, providing an additional visual representation of the selected currency.

---

## 📊 Dynamic Conversion

After receiving the exchange rate, JavaScript processes the response and dynamically updates the conversion result displayed on the page.

---

## ⚠️ Error Handling

The application accounts for common user and network conditions, including:

- Missing amount values.
- Invalid input.
- Failed API requests.
- Network errors.
- Unexpected API responses.

---

# 📂 Project Structure

```text
currency-converter/
│
├── index.html
├── style.css
├── app.js
├── codes.js
│
└── README.md
```

---

## 📄 File Responsibilities

| File | Responsibility |
|------|----------------|
| `index.html` | Defines the application structure and UI elements |
| `style.css` | Handles layout, styling, responsiveness, and visual design |
| `app.js` | Handles conversion logic, API requests, events, and dynamic UI updates |
| `codes.js` | Contains currency and country-code mapping data |
| `README.md` | Project documentation |

---

# 🌍 Supported Currencies

The application supports a wide range of international currencies.

### Example Conversions

| From | To |
|------|----|
| USD | INR |
| INR | JPY |
| EUR | GBP |
| CAD | AUD |
| SAR | INR |
| USD | EUR |
| GBP | INR |
| JPY | USD |

The available currency options depend on the currency data provided by the application and the integrated exchange-rate service.

---

# 💡 Skills Demonstrated

## 🌐 Frontend Development

- Responsive Web Design
- UI Development
- CSS Layout Techniques
- Flexbox
- Responsive Styling
- User Experience Design

---

## ⚡ JavaScript Development

- DOM Manipulation
- Event Handling
- Fetch API
- Promises
- Asynchronous Programming
- JSON Parsing
- Dynamic Rendering
- Error Handling

---

## 🔌 API Integration

- REST API Consumption
- HTTP Requests
- External Service Integration
- JSON Data Processing
- Dynamic Data Handling

---

## 🧠 Problem Solving

- Handling dynamic user input.
- Managing asynchronous operations.
- Mapping currencies to country codes.
- Updating multiple UI elements from API data.
- Handling unsuccessful requests.
- Maintaining a responsive user experience.

---

# 🎯 Learning Outcomes

Through this project, I strengthened my understanding of:

- REST API integration.
- Fetch API.
- Asynchronous JavaScript.
- Promises.
- JSON data processing.
- DOM manipulation.
- Event-driven programming.
- Dynamic UI rendering.
- Error handling.
- Responsive web development.
- Data-driven frontend applications.

---

# ⚡ Performance

The application follows a lightweight frontend architecture focused on simplicity and responsiveness.

### Performance Considerations

- Lightweight HTML structure.
- Minimal external dependencies.
- Client-side conversion processing.
- Efficient DOM updates.
- Responsive CSS layout.
- Asynchronous API requests.

---

# 🌐 Browser Support

| Browser | Support |
|---------|:-------:|
| Google Chrome | ✅ |
| Microsoft Edge | ✅ |
| Mozilla Firefox | ✅ |
| Safari | ✅ |
| Opera | ✅ |

---

# 🚀 Future Enhancements

The project can be extended with additional features such as:

### 📊 Data & Analytics

- Historical exchange rates.
- Currency trend charts.
- Exchange-rate analytics.
- Daily rate comparisons.

### ⭐ User Features

- Favorite currency pairs.
- Conversion history.
- Recently used currencies.
- Custom currency preferences.

### 🎨 User Experience

- Dark mode.
- Multiple themes.
- Multi-language support.
- Improved animations.

### 📱 Advanced Features

- Progressive Web App (PWA).
- Offline support.
- Exchange-rate alerts.
- Installable mobile experience.

---

# 📈 Project Highlights

- ✅ Real-Time Currency Conversion
- ✅ REST API Integration
- ✅ Fetch API Implementation
- ✅ Asynchronous JavaScript
- ✅ Dynamic Currency Selection
- ✅ Dynamic Country Flags
- ✅ Currency Swap Functionality
- ✅ JSON Data Processing
- ✅ Error Handling
- ✅ Responsive User Interface
- ✅ Modern Frontend Development
- ✅ Portfolio Ready

---

# ⚠️ Disclaimer

This project was developed for **educational and portfolio purposes** to demonstrate frontend development, JavaScript programming, and external API integration.

Exchange-rate values are provided by the integrated external service and may change over time. The application should not be considered a financial or investment tool.

---

# 👨‍💻 Developer

## Mohammad Naveed

**Aspiring Java Full Stack Developer**

Passionate about building modern and scalable web applications while continuously developing skills in:

- Java
- Spring Boot
- React
- JavaScript
- REST APIs
- Cloud Computing
- Software Engineering
- System Design

---

# 🌐 Connect With Me

### GitHub

https://github.com/mdnav

### LinkedIn

https://www.linkedin.com/in/mdnav/

---

# 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

If you'd like to contribute:

1. Fork the repository.
2. Create a new feature branch.

```bash
git checkout -b feature/your-feature
```

3. Make your changes.
4. Commit your changes.

```bash
git commit -m "Add: your improvement"
```

5. Push your branch.

```bash
git push origin feature/your-feature
```

6. Open a Pull Request.

---

# ⭐ Support

If you found this project useful or interesting, consider supporting it by:

⭐ **Starring the repository**

🍴 **Forking the project**

💬 **Sharing feedback**

Your support motivates me to continue learning, building, and sharing more projects.

---

<div align="center">

## 🚀 Thanks for Visiting!

If you enjoyed exploring **Real-Time Currency Converter**, don't forget to **⭐ Star the repository**.

**Made with ❤️ by Mohammad Naveed**

### Always Learning • Always Building • Always Improving

</div>
