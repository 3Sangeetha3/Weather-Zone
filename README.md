<h1 align="center"> Weather Dashboard </h1>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,vite,tailwind" />
  </a>
</p>

## 📝 What is in this Repositry?

Weather Dashboard is a modern, interactive weather forecasting application built with React and Vite. It provides real-time weather updates, a 5-day forecast, and convenient search history, empowering you to quickly get current weather information for any city.

## Preview 

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/3sangeetha3/PicLink@Images-branch/images/1743284981817-476443795.png" alt="Home Page" width="800">
  <em>Home Page</em>
</p>

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/3sangeetha3/PicLink@Images-branch/images/1743284863914-940012623.png" alt="Home Page Continued" width="800">
  <em>Error Page </em>
</p>


## ✨ Key Features

- **Real-Time Weather Data:** Search for any city to get the current temperature, humidity, wind speed, and weather conditions.
- **5-Day Forecast:** View detailed weather forecasts for the upcoming days with icons and descriptions.
- **Search History:** Quickly access your recent searches to streamline your experience.
- **Temperature Unit Toggle:** Easily switch between Celsius and Fahrenheit.
- **Responsive & Modern UI:** Built using Tailwind CSS and React for a clean and engaging interface.

### 💻 User Experience

- **Responsive Design**: Optimized for all devices from mobile to desktop
- **Dark Mode Interface**: Elegant dark-themed UI that's easy on the eyes
- **Loading States**: Visual feedback while weather data is being fetched
- **Error Handling**: Clear error messages when searches don't return results


## 🛠️ Built With

- **React 19** - UI library
- **Vite** - Build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **Axios** - Promise-based HTTP client
- **Lucide React** - Icon set
- **OpenWeatherMap API** - Weather data provider



### 🔧 Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/3Sangeetha3/Zynetic.git
cd zynetic
```
2. **Install dependencies**
```bash
npm install
```
3. **Configure Environment Variables:**
- Create a .env file in the project root
```bash
VITE_OPENWEATHER_API_KEY=your_api_key_here
```
4. **Run the Application:**
```bash
npm run dev
```
-Open your browser and visit http://localhost:5173 to see the app in action.

### 🐳 Option 2: Run with Docker
Perfect for deploying on a server like AWS EC2, DigitalOcean, etc.


## 🐳 Option 2: Run with Docker

> Perfect for deploying on a server like AWS EC2, DigitalOcean, etc.

### ✅ Prerequisites

- Docker installed on your system
- An OpenWeather API key from [https://openweathermap.org](https://openweathermap.org)

---

## ⚙️ Steps

### 1. Pull the Docker image

```bash
docker pull 3sangeetha3/zynetic-weather-zone
```

### 2. Run the container
```bash
docker run -d -p 5173:5173 --name zynetic \
  -e VITE_OPENWEATHER_API_KEY=your_openweather_api_key_here \
  3sangeetha3/zynetic-weather-zone
```
### 3. Visit the app

- On a **cloud server** (like EC2):  
  `http://<your-public-ip>:5173`

- On your **own machine**:  
  `http://localhost:5173`

> 💡 **Important:** Ensure that port `5173` is open in your EC2 security group or local firewall settings.



### 📂 Project Structure
```bash
zynetic/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── WeatherCard.jsx
│   │   ├── Footer.jsx
│   │   └── Button.jsx
│   ├── services/
│   │   └── weatherApi.js
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .env
├── package.json
└── README.md
```
### Deployment on cloudflare

- **Live Link:** [weather-zone.pages.dev](https://weather-zone.pages.dev/)
- **Cloudflare Link:** [https://weather-zone.pages.dev/](https://weather-zone.pages.dev/)


<p align="center"> Made with ❤️ by Sangeetha Choudhary </p>