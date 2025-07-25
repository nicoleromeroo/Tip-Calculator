
# Tip Calculator

A simple full-stack Tip Calculator built with **Spring Boot** (Java) and **Vanilla JavaScript**. Users can input the bill amount, tip percentage, and number of people to split the bill. The app calculates the tip, total amount, and amount per person via a REST API.

---

## Features

- REST API built with Java + Spring Boot
- HTML/CSS frontend with Vanilla JS
- Real-time calculation of:
  - Tip amount
  - Total amount
- Clean, responsive UI
- Beginner-friendly and easy to extend

---

## Tech Stack

| Layer     | Technology         |
|-----------|--------------------|
| Backend   | Java 17, Spring Boot |
| Frontend  | HTML, CSS, Vanilla JavaScript |
| API Style | REST (JSON-based) |
| Tools     | Maven, Postman (testing) |

---

## Getting Started

### Prerequisites

- Java 17+
- Maven
- Netlify
- Render

### 1. Clone the Repository

```bash
git https://github.com/nicoleromeroo/Tip-Calculator.git
cd tip-calculator

### Project Structure

tip-calculator/
├── backend/
│   └── src/main/java/com/example/tipcalc/
│       ├── controller/TipController.java
│       ├── model/TipRequest.java
│       ├── model/TipResponse.java
│       └── service/TipCalculatorService.java
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
└── README.md
