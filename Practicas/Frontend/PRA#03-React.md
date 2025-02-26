# PRA#03-React: Weather App

## CIFO La Violeta - FullStack IFCD0210-25 MF01

In this practical exercise, you will enhance the existing Weather App by implementing advanced React features, improving the user interface, and adding new functionalities.

## Objectives

> Expand the Weather App to include multiple pages, save favorite cities, and improve the overall user experience with Material-UI components.

### Project References

**Project Base**

- Starting point: [Weather App Repository](https://github.com/AlbertProfe/weatherApp)
- PronunciationApp (MUI, Forms and Leaflet): [PronunciationApp]([GitHub - AlbertProfe/pronunciationApp](https://github.com/AlbertProfe/pronunciationApp/tree/master))

**Libraries**

- React Documentation: [React Router](https://reactrouter.com/en/main)
- Material-UI Documentation: [Getting Started with Material-UI](https://mui.com/material-ui/getting-started/)
- A composable charting library built on React components: [Recharts](https://recharts.org/en-US/)
- Simply Visualize, Highcharts: [Highcharts](https://www.highcharts.com/)
- React components for Leaflet maps: [Leaflet](https://react-leaflet.js.org/)

### Tasks

- [ ] Implement React Router for multi-page navigation
- [ ] Create new pages: Home, Weather, Map, and About
- [ ] Add functionality to save favorite cities
- [ ] Enhance UI with Material-UI components
- [ ] Implement a map feature for weather visualization

### Tasks Description

1. **Implement React Router**
   
   - Install React Router: `npm install react-router-dom`
   - Set up routes for `Home`, `Weather`, `Map`, and `About` pages
   - Create a navigation component to switch between pages

2. **Create New Pages**
   
   - Develop separate components for `Home`, `Weather`, `Map`, and `About` pages
   - <mark>Home</mark>: Display a welcome message and quick links to other pages
   - <mark>Weather</mark>: Keep the existing weather search and display functionality
   - <mark>Map</mark>: Implement a map view for weather data (you can use libraries like react-leaflet)
   - <mark>About</mark>: Add information about the app and its features

3. **Save Favorite Cities**
   
   - Implement a feature to mark cities as favorites
   - Use local storage to persist favorite cities
   - Display a list of favorite cities for quick access

4. **Enhance UI with Material-UI**
   
   - Install Material-UI: `npm install @mui/material @emotion/react @emotion/styled`
   - Replace existing CSS with Material-UI components
   - Implement a **responsive layout using Material-UI's Grid system**
   - Use Material-UI's <mark>theming</mark> to create a cohesive design

5. **Implement Map Feature**
   
   - Integrate a map library (e.g., `react-leaflet`) to display weather data geographically
   - Show weather icons on the map for searched or favorite cities
   - Implement click interactions on the map to fetch weather data for clicked locations

## Advanced Customization (Optional)

To further enhance your Weather App, consider implementing these advanced features:

1. **Dark Mode Toggle**
   
   - Implement a dark mode using Material-UI's theming capabilities
   - Add a toggle switch to change between light and dark modes

2. **Historical Weather Data**
   
   - Add a feature to view historical weather data for a selected location
   - Implement a date picker to select the date for historical data

3. **Weather Comparison**
   
   - Allow users to compare weather between two or more cities side by side
   - Implement a **comparison chart using a charting library like `recharts`**

### Submission Guidelines

- Fork the existing [Weather App Repository](https://github.com/AlbertProfe/weatherApp) and clone to local
- Create a new branch named `PRA03-YourName`
- Commit your changes with clear, descriptive messages
- Push your branch to your **forked repository**
- Create a **pull request** to the original repository with a summary of your changes, titled:
  - `PRA#03_React-YourName-WeatherApp`

Good luck with your implementation! Focus on creating a user-friendly interface and maintaining clean, efficient code structure.Leaflet<mark></mark>
