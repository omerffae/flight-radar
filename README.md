# Kütüphaneler

- @splidejs/react-splide
- @reduxjs/toolkit
- react-redux
- react-router-dom
- leaflet
- react-leaflet
- leaflet-rotatedmarker
- react-paginate
- bootstrap
- axios

# Kaynaklar

- API: https://rapidapi.com/apidojo/api/flight-radar1

# Flight Radar Application

A modern web application that allows users to track and monitor flights in real-time. Built with React and Redux, this application provides both map and list views of flight data.

![Proje Görseli](/public/flight_radar.gif)  

## 🚀 Features

- Real-time flight tracking
- Interactive map view
- Detailed list view of flights
- Modal-based detailed flight information
- Responsive design
- Error handling and loading states

## 🛠️ Technologies Used

- React.js
- Redux for state management
- React Router for navigation
- Modern CSS for styling
- Map integration for flight visualization

## 📁 Project Structure

```
src/
├── components/         # Reusable UI components
│   ├── header.jsx     # Navigation header
│   ├── loader.jsx     # Loading state component
│   ├── error.jsx      # Error handling component
│   └── modal/         # Modal components
├── pages/             # Main application pages
│   ├── map.jsx        # Map view of flights
│   └── list.jsx       # List view of flights
├── redux/             # State management
│   ├── actions/       # Redux actions
│   ├── slices/        # Redux slices
│   └── store.js       # Redux store configuration
├── utils/             # Utility functions
├── App.jsx            # Main application component
└── main.jsx          # Application entry point
```

## 🚀 Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## 📱 Application Views

### Map View
- Interactive map showing flight positions
- Real-time flight tracking
- Click on flight markers for detailed information

### List View
- Tabular display of flight information
- Sortable and filterable flight data
- Quick access to flight details

## 🔧 Configuration

The application uses environment variables for configuration. Make sure to set up your environment variables in a `.env` file:

```env
VITE_API_KEY=your_api_key
```

## 👥 Authors

- Ömer Ekin 

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape this project
- Special thanks to the flight data API providers