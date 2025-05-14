# MyWatt - Smart Home Application

MyWatt Smart Home App is designed to enhance smart home energy management by providing real-time energy monitoring, device automation and sustainability insights. The Application was developed using React Native for frontend, Python (flask) for backend functions and Supabase for database management. This was done over the course of 6 months as part of a university group project. I mostly worked in developing backend functionalities for the application along with the database management.

Company LinkedIn : https://www.linkedin.com/company/mywatt-co/

## Installation and Set up
## Prerequisites
Ensure you have the following installed:
• Node.js (LTS version) - Download
• pnpm (for package management)
• Expo CLI (for development and testing)
• Android Studio (for Android development)
• Xcode (for iOS development on macOS)
-- Install Dependencies
1. Install pnpm globally:
`npm install -g pnpm`
2. Install Expo CLI:
`pnpm add -g expo-cli`

## Create and Start the Project
Initialize a new project:
expo init react-native-app.
1. `cd react-native-app`
2. Start the development server:
`pnpm start`
3. Run on a device/emulator:
o Android Emulator:
`pnpm expo run:android`
o iOS Simulator (macOS only):
`pnpm expo run:ios`
o Physical Device: Scan the QR code from Expo Developer Tools using the
`Expo Go app`

## Maintenance & Updates
Updating Dependencies
1. To update dependencies, run:
`pnpm update`
2. Building the App
To generate the final production build:
`expo prebuild`
`expo build`

-- For Android:
`expo build:android`

-- For iOS:
`expo build:ios`

-- For detailed explanation just use `pnpm start` and command line will show you command that you need to put in the terminal
## Running the App
1. Open a terminal.
2. Run `pnpm start`
3. Open the app using an emulator or Expo Go
