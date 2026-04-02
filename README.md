# Monastry-360
An interactive web application for exploring Buddhist monasteries in Sikkim, India. Features an interactive map powered by OpenStreetMap (completely free!) with detailed monastery information, search functionality, and location services.

Features
🗺️ Interactive Free Map - View monasteries with custom markers and info windows (powered by OpenStreetMap)
🔍 Advanced Search & Filtering - Search by name, features, or filter by sect and altitude
📍 Location Services - Detect user location and calculate distances to monasteries
📱 Responsive Design - Works on desktop and mobile devices
🏛️ Detailed Monastery Info - Comprehensive details including history, features, and nearby attractions
🎨 Beautiful UI - Modern design inspired by Buddhist aesthetics
💰 100% Free - No API keys, no billing, no payments required!
Setup Instructions
1. Install Dependencies
npm install
2. Run the Application
That's it! No API keys or billing setup required! 🎉

The app uses OpenStreetMap via Leaflet, which is completely free and doesn't require any registration or API keys.

npm run dev
The application will be available at http://localhost:5173

Why OpenStreetMap?
We chose OpenStreetMap over Google Maps because:

✅ Completely Free - No API keys, no billing, no usage limits
✅ No Registration Required - Start using immediately
✅ Open Source - Community-driven mapping data
✅ High Quality - Excellent coverage for Sikkim and surrounding areas
✅ Privacy Friendly - No tracking or data collection
✅ Reliable - Used by millions of applications worldwide
Monastery Data
The app includes comprehensive data for 8 major monasteries in Sikkim:

Rumtek Monastery - Kagyu sect, founded 1966
Pemayangtse Monastery - Nyingma sect, founded 1705
Tashiding Monastery - Nyingma sect, founded 1641
Enchey Monastery - Nyingma sect, founded 1909
Dubdi Monastery - Nyingma sect, founded 1701
Phodong Monastery - Kagyu sect, founded 1740
Lachung Monastery - Nyingma sect, founded 1880
Ralang Monastery - Kagyu sect, founded 1768
Each monastery entry includes coordinates, visitor statistics, features, nearby attractions, and detailed descriptions.

Usage
Map View: Browse monasteries on the interactive OpenStreetMap
Search: Use the search bar to find monasteries by name or features
Filters: Filter by Buddhist sect or altitude range
Location: Allow location access to see distances from your position
Details: Click on monastery markers or list items for detailed information
Navigation: Toggle between map and list views
Technical Stack
React 18 with TypeScript
Vite for build tooling
Leaflet & React-Leaflet for interactive maps (OpenStreetMap)
Tailwind CSS for styling
Lucide React for icons
Radix UI for accessible components
Development
The project structure:

src/
├── components/
│   ├── LeafletMap.tsx         # Interactive Leaflet Map component (OpenStreetMap)
│   ├── MapScreen.tsx          # Main map screen with search/filters
│   ├── MonasteryFilters.tsx   # Search and filtering components
│   └── ui/                    # Reusable UI components
├── data/
│   └── monasteries.ts         # Monastery data and types
├── hooks/
│   └── useLocation.ts         # Location services hook
└── ...
License
This project is for educational and demonstration purposes.
