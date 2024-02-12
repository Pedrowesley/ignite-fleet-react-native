# React Native - Vehicle Management Application 🚗

![Figma Image](/.screenshoot/main.png)

This is a React Native application offering features to **register and manage vehicle usage within companies**. The app allows employees to record company vehicle usage and provides authentication features and integration with map APIs and databases.

## Table of Contents

- [Installation](#installation)
- [Configuration](#configuration)
- [Features](#features)
- [Documentation](#documentation)
- [Used Libraries and Technologies](#used-libraries-and-technologies)
- [License](#license)

## Installation 🛠️

Before getting started, make sure you have the React Native development environment set up on your machine. Follow the [installation instructions](https://reactnative.dev/docs/environment-setup) in the official React Native documentation.

1. **Clone the repository:**

   ```
   git clone https://github.com/Pedrowesley/ignite-fleet-react-native.git
   ```

2. **Navigate to the project directory:**

   ```
   cd ignite-fleet-react-native
   ```

3. **Install the project dependencies:**

   ```
   npm install
   ```

4. **Start the application:**

   ```
   npm start
   ```

   This will start the Metro Bundler and provide options to run the app on emulators or physical devices.

## Configuration ⚙️

To use the app, some environment variables and external service integrations need to be configured. Follow these steps:

### Environment Variables 🔑

The app uses environment variables to store sensitive information like API keys and URLs. Create a `.env` file at the root of the project and configure the following variables:

```
API_BASE_URL=https://your-api-url.com
GOOGLE_MAPS_API_KEY=your-google-maps-api-key
```

### OAuth  2.0 Authentication 📝

The app uses OAuth  2.0 for user authentication. Refer to the documentation on setting up OAuth  2.0 for more information.

### Database Configuration 🗄️

The app uses RealmDB to store data. Ensure RealmDB is installed in the project and configure the database schemas as needed.

## Features 🚀

The application offers the following main features:

- Vehicle Usage Registration 📋
- User Authentication 🔐
- Integration with Map APIs (Google Maps) 🗺️
- Data Storage in RealmDB 🏦
- Address Geocoding  🌍
- Interactive Maps Display 🗺️
- Map Marker Customization 📍
- Background Tasks ⏲️

## Documentation 📚

For detailed information on how to use the application, consult the documentation available in the `docs` directory of this repository. The documentation includes step-by-step guides, code examples, and information on integrating with external services.

## Used Libraries and Technologies 📦

The application was developed using the following libraries and technologies:

- React Native
- Styled Components
- React Navigation
- Expo Location
- React-Native-Maps
- OAuth  2.0
- RealmDB

Check the `package.json` file for the complete list of project dependencies.

## License 📜

This project is licensed under the MIT License. See the `LICENSE` file for more details.
