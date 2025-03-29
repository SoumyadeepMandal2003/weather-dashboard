# 🌤️ Weather Dashboard

A modern and responsive weather dashboard built with React.js and the OpenWeatherMap API. Users can search for any city and view real-time weather updates, including temperature, conditions, humidity, and wind speed.

## 🚀 Live Demo
🔗 [View the Live App](https://your-deployment-url.vercel.app)

## 📸 Screenshots
![Weather Dashboard Preview](https://your-screenshot-url.com)

---

## 🛠️ Features
- ✅ **Search for Any City** – Get real-time weather updates
- ✅ **Live Data from OpenWeatherMap API**
- ✅ **Clean and Responsive UI**
- ✅ **Recent Search History** – Saves last 5 searches
- ✅ **Error Handling** – Alerts for invalid cities or API failures

---

## 🏗️ Tech Stack
- **Frontend**: React.js, Tailwind CSS
- **API**: OpenWeatherMap API
- **Deployment**: Vercel / GitHub Pages / Netlify

---

## 🔧 Setup Instructions
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/weather-dashboard.git
cd weather-dashboard
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file in the root directory and add your OpenWeatherMap API key:
```env
VITE_API_KEY=your_openweathermap_api_key
```

### 4️⃣ Run the App Locally
```bash
npm run dev
```

## 🌍 API Integration
- **API Used**: OpenWeatherMap Current Weather API
- **Endpoint**: `https://api.openweathermap.org/data/2.5/weather?q={city}&appid={YOUR_API_KEY}&units=metric`
- **Rate Limits**: Free tier allows up to 60 requests per minute.
