# Weather Dashboard

A beautiful, responsive weather dashboard that fetches real-time weather data from the OpenWeatherMap API.

## 🌤️ Features

- **Real-time Weather Data** - Current conditions, temperature, humidity, pressure, wind speed
- **5-Day Forecast** - Visual forecast for the next 5 days
- **Location-based Weather** - Get weather for your current location using geolocation
- **Temperature Units** - Toggle between Celsius and Fahrenheit
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- **Beautiful UI** - Modern glassmorphism design with smooth animations
- **Weather Icons** - Dynamic icons based on weather conditions
- **Fast & Reliable** - Uses OpenWeatherMap free API

## 🚀 Quick Start

1. Open `weather-dashboard.html` in any modern web browser
2. The dashboard loads with weather for London by default
3. Search for any city using the search box
4. Click "My Location" to get weather for your current location
5. Toggle between °C and °F for your preferred temperature unit

## 📋 What You Can Do

### Search Weather
- Type any city name in the search box and press Enter or click Search
- Get instant weather information for that location

### Use Your Location
- Click the "My Location" button to automatically fetch weather for your current location
- Requires location permission from your browser

### View Detailed Information
The dashboard displays:
- Current temperature and weather condition
- "Feels Like" temperature
- Humidity percentage
- Atmospheric pressure
- Wind speed
- Visibility
- Cloud coverage
- 5-day forecast with daily temperatures and conditions

### Change Temperature Units
- Click °C or °F to toggle between Celsius and Fahrenheit
- Your preference applies to all data displayed

## 🔧 Technical Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **API:** OpenWeatherMap Free Tier
- **Styling:** Gradient backgrounds, Glassmorphism effects, CSS Animations
- **Icons:** Font Awesome 6.4.0
- **Fonts:** Google Fonts (Poppins)
- **Features:** Responsive Grid Layout, Flexbox, CSS Transitions

## 📡 API Information

This dashboard uses the **OpenWeatherMap API** (free tier):
- Current Weather API: `/weather` endpoint
- Forecast API: `/forecast` endpoint
- API Key: Included in the code

**Note:** The free tier has limitations:
- 60 requests per minute
- 1,000 requests per day
- Current weather + 5-day forecast data

To use your own API key:
1. Sign up at [OpenWeatherMap](https://openweathermap.org/api)
2. Get your free API key
3. Replace `API_KEY` variable in the script with your key

## 📊 Displayed Weather Data

### Current Weather Card
- City name and country
- Current temperature with weather icon
- Weather description
- Feels like temperature
- Humidity
- Atmospheric pressure
- Wind speed (converted to km/h)
- Visibility
- Cloud coverage

### 5-Day Forecast
- Day of week
- Weather icon for each day
- Forecasted temperature

## 🎨 Design Features

- **Gradient Background:** Purple gradient for visual appeal
- **Glassmorphism Cards:** Semi-transparent cards with backdrop blur
- **Smooth Animations:** Fade-in effects, floating icons, hover animations
- **Color-coded Weather:** Icons change color based on weather type
- **Responsive Grid:** Automatically adjusts layout for different screen sizes
- **Interactive Elements:** Buttons with hover effects and transitions

## 🌐 Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Mobile Optimization

- Touch-friendly buttons and inputs
- Responsive font sizes
- Optimized layout for smaller screens
- Efficient API calls

## 🔐 Privacy & Security

- No user data is stored
- Geolocation data is used only for weather fetching
- All API calls are made securely over HTTPS
- No tracking or analytics

## 🐛 Troubleshooting

### "City not found" error
- Check spelling of city name
- Try with a different city name
- Ensure internet connection is active

### Geolocation not working
- Enable location access for your browser
- Check browser permissions
- Try a different browser if issues persist

### No data displayed
- Check your internet connection
- Verify API is accessible (OpenWeatherMap might be down)
- Clear browser cache and reload

## 📈 Future Enhancements

Potential features to add:
- Multiple city comparison
- Weather alerts and warnings
- Historical weather data
- Air quality index
- UV index
- Sunrise/sunset times
- Weather maps
- Saved favorite locations
- Dark/Light theme toggle

## 📝 Files

- `weather-dashboard.html` - Complete weather dashboard (standalone file)
- `README.md` - Documentation

## 🎯 How to Deploy

### GitHub Pages
1. Go to repository Settings
2. Find "Pages" section
3. Select main branch as source
4. Wait for deployment
5. Access at: `https://yourusername.github.io/Portfolio-Website-of-Shah-Umair-/weather-dashboard.html`

### Other Hosting Options
- Netlify
- Vercel
- Any static hosting service
- Local web server

Simply upload the HTML file and open it in a browser!

## 📞 Support

For issues or questions:
- Check the troubleshooting section above
- Verify your internet connection
- Try a different browser
- Clear cache and cookies

## 📄 License

Feel free to use and modify this weather dashboard as needed.

---

**Last Updated:** June 2026
**Made with ❤️ by Shah Umair**
