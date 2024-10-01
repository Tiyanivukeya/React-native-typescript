
Chef's Menu App

Description
The Chef's Menu App is a simple and user-friendly mobile application built using React Native and TypeScript. This app allows chefs to create, view, and manage their restaurant menu items effortlessly. The app offers features like adding menu items with details such as dish name, description, course type, and price, and displays the complete menu with the total number of items available. It is designed to help chefs quickly prepare and visualize their menu in an organized manner.

Features
- Add Menu Items: The chef can add new dishes to the menu by providing the dish name, description, selecting the course (e.g., Starters, Mains, Dessert), and entering the price.
- View Menu: The home screen displays a list of all menu items that the chef has added, along with the total number of items.
- Course Selection: The app offers a predefined list of courses that chefs can select from while adding a new menu item.
- Basic Animations: Interactive animations enhance the user experience when adding items to the menu.
- Navigation: The app uses React Navigation to enable seamless transitions between the Home screen and the Add Item screen.

Technologies Used
- React Native: For building the mobile app interface.
- TypeScript: To add static typing and enhance code quality.
- React Navigation: For navigating between different screens in the app.
- React Native Animations: To improve the user experience with simple animations.

Getting Started

Prerequisites
- Node.js and npm installed
- React Native CLI or Expo CLI installed

Installation
   
2. Navigate to the project directory:
   
   cd chef-menu-app
   
3. Install the required dependencies:
   
   npm install
   
4. Start the React Native server:
   
   npx react-native start
   

Running the App
- For Android, open an emulator and run:
  
  npx react-native run-android
  
- For iOS, open a simulator and run:
  
  npx react-native run-ios
  

Usage
1. Start the app, and you will be taken to the Home screen.
2. Click on the "Add New Item" button to navigate to the Add Item screen.
3. Fill in the dish details: name, description, course type, and price.
4. Click "Add Item" to save the dish to the menu, which will be displayed on the Home screen.
5. View the complete menu along with the total number of items available.

Screen Recording
A screen recording of the app demonstrating all features is available on YouTube: [Unlisted YouTube Link Here]

Future Improvements
- Add persistent data storage using AsyncStorage or a backend database.
- Implement an edit and delete feature for menu items.
- Add image uploads for menu items.