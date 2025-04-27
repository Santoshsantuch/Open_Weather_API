Weather App (Spring Boot + OpenWeatherMap API)
A web-based application built using Spring Boot that fetches and displays real-time weather data for any city using the OpenWeatherMap API.

🛠️ Tech Stack
Programming Language: Java

Framework: Spring Boot

Frontend: Thymeleaf, HTML, CSS

API Integration: OpenWeatherMap API

Build Tool: Maven

✨ Features
Search for weather by city name

Display current temperature, humidity, wind speed, and weather description

Responsive UI using Thymeleaf templates and basic CSS

Error handling for invalid city inputs

🚀 Getting Started
Clone the repository:

bash
Copy
Edit
git clone <repository-url>
Get your API key from OpenWeatherMap.

Configure the API key in the application.

Run the Spring Boot application:

bash
Copy
Edit
mvn spring-boot:run
Access the app at http://localhost:8080/weather

📂 Main Functionalities

Feature	Description
Search City Weather	Enter a city name to fetch weather
Real-time Weather Details	Temperature, humidity, wind speed
Error Handling	Alerts for invalid city inputs
📌 Notes
Backend fetches weather data using RestTemplate.

UI is kept simple and responsive with basic HTML/CSS.

API key management is externalized for security.
