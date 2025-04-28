
# Travel Itinerary App

This project is a Travel Itinerary App built with React and Vite. The app allows users to create, view, and delete travel itineraries for their trips.

## Features

- **Select a trip**: View details of a selected trip.
- **Add a new trip**: Add a new itinerary with trip details.
- **Delete a trip**: Remove an itinerary from your list.

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **Vite**: Build tool that aims to provide a faster and leaner development experience.
- **ESLint**: A static code analysis tool for identifying and reporting on patterns in JavaScript.

## Setup and Installation

To get started with this project, follow the steps below:

1. Clone the repository:

   ```bash
   git clone https://github.com/Anant110/travel-itinerary-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd travel-itinerary-app
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Run the development server:

   ```bash
   npm run dev
   ```

5. Open the app in your browser:

   ```bash
   http://localhost:3000
   ```

## File Structure

### `public/`
This folder contains the public assets and static files for the app.

- **`index.html`**: The main HTML file that serves as the entry point for the app. It includes the root element where the React app is mounted.

### `src/`
This folder contains all the React components and app logic.

- **`App.js`**: The root component that manages the overall structure of the app. It handles the main layout and routing of the app.
- **`components/`**: A folder containing all reusable React components used within the app.
  - **`TripList.js`**: A component that renders a list of trips.
  - **`TripItem.js`**: A component that displays details of an individual trip.
  - **`AddTripForm.js`**: A form component to add new trips to the itinerary.
- **`styles/`**: Contains all the CSS/SCSS files for styling the app.
  - **`App.css`**: The main stylesheet for styling the app.
  - **`TripList.css`**: Styles for the `TripList` component.
  - **`AddTripForm.css`**: Styles for the `AddTripForm` component.
- **`utils/`**: A folder for utility functions.
  - **`api.js`**: Contains functions for interacting with a mock or real backend API for fetching, adding, and deleting trips.
  
### `gitignore`
Specifies which files and directories should be ignored by Git. This includes node modules, build files, and other unnecessary files from version control.

### `package.json`
Contains metadata about the project and lists the dependencies required for the app to run, as well as the scripts for development and production.

### `vite.config.js`
The configuration file for Vite, which is the build tool used in the project. It defines settings for development and production builds, as well as any plugins used in the project.

### `eslint.config.js`
Contains the configuration for ESLint, which helps in identifying and fixing linting issues in the codebase to maintain code quality.

### `README.md`
This file! It explains the project structure, setup instructions, and other important information related to the project.

## Component Hierarchy

- **App**: The root component that contains the main structure of the app.
- **TripList**: A component that lists all trips.
- **TripItem**: Displays individual trip details in the list.
- **AddTripForm**: A form to add new trips to the itinerary.

## Challenges Faced

- **State Management**: Managing the state of the trips in the app was a challenge, particularly when it came to ensuring that the app updated correctly after adding or deleting trips.
- **Responsive Design**: Ensuring that the app works well across different screen sizes required adjustments to the CSS and use of responsive design techniques.
- **Routing**: Implementing routing between different views of the app, such as viewing a selected trip and adding new trips, was initially confusing but was resolved by setting up React Router.

## GitHub Repository

You can find the complete project on GitHub: [Travel Itinerary App GitHub Repository](https://github.com/Anant110/React-Project)

## Contributions

Feel free to fork the repository and submit pull requests. All contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
