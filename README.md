# Note-Taking App

A simple React Native note-taking app where users can create, edit, and delete notes linked to clients and categories.

## Features

- **Create Notes**: Users can add new notes, selecting a client and a category for each note.
- **View Notes**: The home screen displays a list of all notes using a FlatList.
- **Edit and Delete Notes**: Users can edit the details of a note or delete it.
- **Client and Category Data**: Client and category data are stored in a JSON file.
- **Persistent Storage**: Notes are stored in local memory, ensuring data persistence across app restarts.

## Categories

- Goal Evidence
- Support Coordination
- Active Duty

## Setup and Installation

This app is built using Expo (SDK 49) and Tailwind CSS for styling. To set up and run the app:

1. **Clone the repository**:

2. **Install Dependencies**:
- Run `npm install` to install all required node modules.
- Run `npx expo install` to install Expo-specific dependencies.

3. **Start the App**:
`npx expo start`


This will start the Expo CLI. You can then run the app on a physical device or an emulator/simulator.

## Important Note

If the app fails to start up, you may need to install a specific version of Tailwind CSS. Run the following command:

`npm install --save-dev tailwindcss@3.3.2`

This installs Tailwind CSS version 3.3.2 as a development dependency, which should resolve any startup issues related to styling.

