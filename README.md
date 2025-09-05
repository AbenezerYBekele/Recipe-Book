# Recipe Finder App
A mobile recipe discovery application for iOS and Android built with Expo (React Native). This app allows users to search for recipes, browse by category, view detailed instructions, and save their favorite meals for later use.
## Screenshots
Home Screen
<p align="center">
   <img src="https://github.com/user-attachments/assets/13f791ea-14b4-4551-b17f-98db5cf33664" alt="Screenshot 4" width="200"/>
  <img src="https://github.com/user-attachments/assets/f7b857e3-a7eb-4435-b103-daae8a60f1e2" alt="Screenshot 3" width="200"/>
  <img src="https://github.com/user-attachments/assets/23560a07-ec5f-4a67-8fa6-55f4166a1a6e" alt="Screenshot 2" width="200"/>
  <img src="https://github.com/user-attachments/assets/d3ec212a-e874-40d0-8eaf-fd32a6dda24f" alt="Screenshot 1" width="200"/>
  </p>

  ## ✨ Features

- **Recipe Search:**  
  Dynamically search for recipes by name with a debounced input to prevent excessive API calls.  

- **Category Browsing:**  
  Explore recipes across popular categories like *Chicken, Beef, Dessert, Vegetarian*, and more.  

- **Detailed Recipe View:**  
  - A list of ingredients with precise measurements  
  - Step-by-step cooking instructions  
  - An embedded YouTube video tutorial for visual guidance  

- **Save for Later:**  
  Save your favorite recipes to a local list for quick and easy access.  
  This list persists even after closing the app.  

- **Share Functionality:**  
  Easily share a link to a recipe with friends and family using the native device sharing options.  

## 🚀 Technology Stack

This project is built using a modern mobile development stack:

- **Framework:** React Native with Expo  
- **Navigation:** Expo Router (File-based routing)  
- **Local Storage:** `@react-native-async-storage/async-storage` for saving favorite recipes  
- **Video Playback:** `react-native-webview` to embed YouTube videos  
- **Language:** JavaScript (ES6+)  
- **Styling:** React Native `StyleSheet` with a centralized `styles.js` file  
- **API:** All recipe data is fetched from the free [TheMealDB API](https://www.themealdb.com/api.php)  

---

## 🔧 Setup and Installation

To run this project locally, follow these steps:

### 1. Prerequisites

- Node.js (LTS version recommended)  
- Git  
- Expo Go app on your physical iOS or Android device  

### 2. Clone the Repository

```bash
git clone https://github.com/your-username/recipe-book.git
cd recipe-book
```

### 3. Install Dependencies
Install all the necessary packages using npm (or yarn).
```bash
npm install
```

### 4. Run the Application
Start the Expo development server. This will provide a QR code in your terminal.
```bash
npx expo start
```
### 5. Open on Your Device
Open the Expo Go app on your phone.
Scan the QR code from the terminal.
The app will bundle and open on your device.



