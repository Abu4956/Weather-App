# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


# Weather-App 🌤️

A responsive and interactive weather application built with React, Vite, and TailwindCSS.  
Users can search for cities to get current weather conditions — including temperature (°C/°F), humidity, wind, visibility and sunrise/sunset times. The app also presents dynamically changing backgrounds based on weather and time of day.

---

## 🔍 Features

- Search for any city (with type-ahead suggestions) and fetch current weather using the [OpenWeatherMap API](https://openweathermap.org/)  
- Toggle temperature unit between Celsius (°C) and Fahrenheit (°F)  
- Visual icons and readable values for key weather metrics: humidity, wind, visibility, sunrise & sunset  
- Dynamic background scenes that adapt to the weather condition and time of day  
- Clean UI built with TailwindCSS and mobile-first responsiveness  

---

## 🧩 Tech Stack

- **Frontend**: React (functional components + hooks)  
- **Bundler / Dev Environment**: Vite  
- **Styling**: TailwindCSS  
- **API**: OpenWeatherMap (weather & geocoding endpoints)  
- **Utilities**: Helper functions for conversion & formatting (temperature, visibility, wind direction etc.)  

---

## 🛠️ Setup & Running Locally

1. Clone the repository  
   ```bash
   git clone https://github.com/Abu4956/Weather-App.git
   cd Weather-App

2. Install dependencies

  ```bash
   Copy code
   npm install
```
3. Add your OpenWeatherMap API key

In the .env or configure directly in the file (make sure not to expose it in production!)
  ```bash
  env
  VITE_OPENWEATHER_API_KEY=your_api_key_here
```
4. Start the development server

  ```bash
   npm run dev
```
   Then open http://localhost:3000 (or the port shown) in your browser.

5. Build for production

 ```bash

  npm run build
```
The output will be in dist/.
---
👨‍💻 Author

Abu Obaida
📧 abuobaidakopaganj@gmail.com
 | 📱 7800260625

📄 License

This project is open source and available under the MIT License
.
