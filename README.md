# Weather Now 🌤️

A clean and intuitive weather application built for outdoor enthusiasts like Jamie who need quick access to current weather conditions for any city worldwide.

## Features

- **Quick City Search**: Simply type any city name to get instant weather data
- **Current Weather Conditions**: Temperature, humidity, wind speed, cloud cover, and atmospheric pressure
- **Weather Icons**: Visual representation of current weather conditions
- **Responsive Design**: Works perfectly on desktop and mobile devices
- **Real-time Data**: Powered by the reliable Open-Meteo API
- **No Authentication Required**: Free to use without any API keys or registration

## Technology Stack

- **Framework**: React 19 with Vite
- **Styling**: Custom CSS with modern design principles
- **API**: Open-Meteo API for weather data and geocoding
- **State Management**: React's built-in useState and useEffect hooks
- **Deployment**: Ready for deployment on any static hosting service

## User Persona

**Name**: Jamie  
**Occupation**: Outdoor Enthusiast  
**Need**: Quick weather condition checks for any city to plan outdoor activities

## API Integration

This application uses two Open-Meteo API endpoints:

1. **Geocoding API**: Converts city names to coordinates
   - `https://geocoding-api.open-meteo.com/v1/search`

2. **Current Weather API**: Fetches real-time weather data
   - `https://api.open-meteo.com/v1/current`

## Getting Started

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd weather-now
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory, ready for deployment.

## Features in Detail

### Weather Information Displayed
- **Current Temperature**: In Celsius with "feels like" temperature
- **Weather Condition**: Clear description with appropriate emoji icons
- **Humidity**: Relative humidity percentage
- **Wind Speed**: Current wind speed in km/h
- **Cloud Cover**: Percentage of sky covered by clouds
- **Atmospheric Pressure**: Current pressure in hPa
- **Last Updated**: Timestamp of the latest data fetch

### User Experience
- **Default Location**: Loads New York weather on first visit
- **Error Handling**: Clear error messages for invalid cities or network issues
- **Loading States**: Visual feedback during data fetching
- **Responsive Design**: Optimized for all screen sizes
- **Accessibility**: Semantic HTML and keyboard navigation support

## Design Philosophy

The application follows modern web design principles:
- **Clean Interface**: Minimal clutter, focus on essential information
- **Visual Hierarchy**: Clear typography and spacing
- **Color Psychology**: Blue gradient background evokes sky and weather
- **Micro-interactions**: Subtle animations enhance user experience
- **Mobile-first**: Responsive design ensures great experience on all devices

## Deployment Options

This application can be deployed on various free hosting services:
- **Netlify**: Drag and drop the `dist` folder
- **Vercel**: Connect your GitHub repository
- **GitHub Pages**: Use GitHub Actions for automatic deployment
- **CodeSandbox**: Import the project directly
- **StackBlitz**: Open the project in the browser

## Future Enhancements

Potential features for future versions:
- 7-day weather forecast
- Geolocation-based weather detection
- Weather alerts and notifications
- Multiple city comparison
- Weather history and trends
- Dark/light theme toggle
- Favorite cities list

## Contributing

Feel free to contribute to this project by:
1. Forking the repository
2. Creating a feature branch
3. Making your changes
4. Submitting a pull request

## License

This project is open source and available under the MIT License.

## Acknowledgments

- **Open-Meteo**: For providing free, reliable weather data
- **React Team**: For the excellent framework
- **Vite**: For the fast development experience

---

Built with ❤️ for outdoor enthusiasts who need reliable weather information at their fingertips.
