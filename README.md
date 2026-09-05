# ✈️ Rocky Travel Agency & AI Travel Assistant

> **An intelligent travel planning project that combines holiday booking with an AI-powered travel assistant.**

## 📌 Overview

**Rocky Travel Agency** is a Python-based travel project developed in **Google Colab**.

The project combines two main components:

1. 🎫 **Travel Booking System** – allows users to select a holiday destination, enter the number of tickets, and calculate the total booking cost.
2. 🤖 **AI Travel Assistant** – allows users to enter a city name and provides weather-related information along with suitable clothing recommendations.

The project demonstrates how traditional programming and AI-based assistance can be combined to create a simple and useful travel application.

---

## ✨ Features

### 🎫 Travel Booking System

The booking system allows users to:

* View available holiday destinations
* Select a destination
* View the price per person
* Enter the number of tickets
* Automatically calculate the total cost
* Receive a booking summary
* Handle invalid destination and ticket inputs

### 🤖 AI Travel Assistant

The AI Travel Assistant is designed to provide travel guidance based on the city entered by the user.

Users can provide a **city name**, and the assistant can provide:

* 🌍 City-based travel information
* 🌤️ Weather information
* 🌡️ Temperature/weather conditions
* 👕 Clothing recommendations
* 🧳 Basic travel suggestions based on weather conditions

### 📊 Graphical & Textual Representation

The AI agent concept is represented through both:

* 📝 **Textual Representation** – explains the user's input, processing, and generated recommendations.
* 📊 **Graphical Representation** – visually represents the AI travel-agent workflow and interaction between the user, AI agent, weather information, and recommendations.

---

## ✈️ Available Holiday Packages

| # | Destination | Price per Person |
| - | ----------- | ---------------: |
| 1 | 🇫🇷 Paris  |           $1,200 |
| 2 | 🇯🇵 Tokyo  |           $1,500 |
| 3 | 🇬🇧 London |           $1,000 |
| 4 | 🇦🇪 Dubai  |             $800 |

---

## 🤖 AI Travel Agent Workflow

The basic workflow of the AI Travel Assistant can be represented as:

```text
                 ┌───────────────────┐
                 │       User        │
                 └─────────┬─────────┘
                           │
                           ▼
                 ┌───────────────────┐
                 │   Enter City Name │
                 └─────────┬─────────┘
                           │
                           ▼
              ┌─────────────────────────┐
              │   AI Travel Assistant   │
              └────────────┬────────────┘
                           │
                    ┌──────┴──────┐
                    ▼             ▼
          ┌────────────────┐  ┌────────────────┐
          │ Weather Info   │  │ Travel Context │
          └───────┬────────┘  └───────┬────────┘
                  │                   │
                  └─────────┬─────────┘
                            ▼
                 ┌─────────────────────┐
                 │ AI Recommendation   │
                 └──────────┬──────────┘
                            │
                 ┌──────────┴──────────┐
                 ▼                     ▼
        ┌─────────────────┐   ┌─────────────────┐
        │ Weather Summary │   │ Clothing Advice │
        └─────────────────┘   └─────────────────┘
```

---

## 🔄 How the Project Works

### Step 1 — Select a Holiday Destination

The user chooses one of the available destinations:

```text
1. Paris
2. Tokyo
3. London
4. Dubai
```

### Step 2 — Enter Number of Tickets

The user enters the required number of tickets.

The program then calculates:

```text
Total Cost = Price per Person × Number of Tickets
```

### Step 3 — Use the AI Travel Assistant

The user can enter a city name.

For example:

```text
Paris
```

The AI Travel Assistant processes the city and provides relevant weather information and clothing recommendations.

### Step 4 — Receive Recommendations

The assistant presents the information in a simple, user-friendly format.

For example:

```text
City: Paris

Weather: Cool and cloudy
Temperature: 15°C

Recommended Clothing:
- Light jacket
- Jeans or trousers
- Comfortable shoes

Travel Suggestion:
Carry a light jacket and prepare for changing weather.
```

---

## 🧠 AI Agent Concept

The AI Travel Assistant follows a simple intelligent-agent concept:

```text
User Input
    ↓
City Identification
    ↓
Weather Information
    ↓
AI Processing
    ↓
Contextual Analysis
    ↓
Travel Recommendation
    ↓
User Output
```

The goal is to demonstrate how an AI agent can take user input, process contextual information, and generate useful recommendations.

---

## 📝 Textual Representation

The textual representation explains the interaction between the user and the AI agent.

### Input

```text
User enters:
"Tokyo"
```

### Processing

```text
AI Agent identifies the city
        ↓
Retrieves/uses weather information
        ↓
Analyzes weather conditions
        ↓
Generates suitable clothing advice
```

### Output

```text
City: Tokyo

Weather Information:
[Weather details]

Recommended Clothing:
[Clothing recommendations]

Travel Advice:
[Weather-based travel suggestions]
```

---

## 📊 Graphical Representation

The graphical representation provides a visual understanding of how the AI Travel Assistant works.

```text
                  USER
                   │
                   ▼
             Enter City
                   │
                   ▼
          ┌────────────────┐
          │   AI AGENT     │
          └───────┬────────┘
                  │
        ┌─────────┴─────────┐
        ▼                   ▼
   Weather Data       Travel Context
        │                   │
        └─────────┬─────────┘
                  ▼
          AI Decision Making
                  │
        ┌─────────┴─────────┐
        ▼                   ▼
     Weather             Clothing
     Summary           Recommendation
        │                   │
        └─────────┬─────────┘
                  ▼
              USER OUTPUT
```

---

## 🛠️ Technologies Used

| Technology                  | Purpose                               |
| --------------------------- | ------------------------------------- |
| 🐍 Python                   | Main programming language             |
| 📓 Google Colab             | Development and execution environment |
| 🤖 AI Agent                 | Intelligent travel recommendations    |
| 🌤️ Weather Information     | Weather-based travel guidance         |
| 📊 Graphical Representation | Visual explanation of agent workflow  |
| 📝 Markdown                 | Project documentation                 |
| 🐙 GitHub                   | Version control and project hosting   |

---

## ▶️ Run the Project in Google Colab

The complete project is available in Google Colab.

### 🚀 Open the Project

**[▶️ Open Rocky Travel Agency in Google Colab](https://colab.research.google.com/drive/1AivKAd3EghJals-VQ9n5yulXJeltv0qA?usp=sharing)**



Google Colab notebooks can contain code, text, comments, and saved outputs, while the runtime environment itself is not shared with the notebook. Therefore, required setup/install cells should be included in the notebook when necessary.

---

## 📂 Project Structure

```text
Rocky-Travel-Agency/
│
├── README.md
│
└── Google Colab Notebook
    │
    ├── Travel Booking System
    │
    ├── AI Travel Assistant
    │
    ├── Textual Representation
    │
    └── Graphical Representation
```

---

## 🎯 Project Objectives

The main objectives of this project are:

* To develop a simple travel booking system using Python.
* To practice user input and conditional logic.
* To calculate travel booking costs automatically.
* To understand the basic concept of an AI agent.
* To demonstrate how an AI agent can process user input.
* To provide weather-based clothing recommendations.
* To represent an AI agent using both graphical and textual methods.
* To combine conventional programming with AI concepts.

---

## 🌟 Example Use Case

Imagine a user is planning a trip to **London**.

The user can:

```text
1. Select London as the holiday destination.
2. Enter the number of tickets.
3. Calculate the total booking cost.
4. Enter London into the AI Travel Assistant.
5. Receive weather information.
6. Get clothing recommendations.
7. Use the recommendations to prepare for the trip.
```

This makes the project more than just a ticket calculator—it demonstrates the concept of an **AI-assisted travel planning system**.

---

## 🔮 Future Improvements

The project can be further improved by adding:

* 🗺️ Interactive maps
* ✈️ Flight search
* 🏨 Hotel recommendations
* 🍽️ Restaurant recommendations
* 💱 Currency conversion
* 📅 Travel itinerary generation
* 🌦️ Multi-day weather forecasting
* 📍 Location-based recommendations
* 💬 Conversational AI interface
* 🌐 Web-based user interface
* 📱 Mobile application
* 💳 Online booking and payment integration

---

## ⚠️ Disclaimer

This project is developed for **educational and demonstration purposes**.

Weather information and AI-generated recommendations should be treated as guidance and may not always represent real-time conditions or professional travel advice.

---

## 👨‍💻 Project Information

**Project:** Rocky Travel Agency & AI Travel Assistant
**Language:** Python
**Platform:** Google Colab
**Repository:** GitHub
**Project Type:** Educational / AI & Python Project

---

## ⭐ Conclusion

**Rocky Travel Agency & AI Travel Assistant** demonstrates how a simple Python-based booking system can be combined with an intelligent travel assistant.

By entering a city, users can receive weather-related information and clothing recommendations, while the graphical and textual representations demonstrate the underlying AI-agent concept.

The project provides a foundation for developing more advanced **AI-powered travel planning applications** in the future.

---

⭐ **Thank you for visiting this project!**
