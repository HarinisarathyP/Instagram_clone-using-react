# 📸 Instagram Clone

---
## 🌐 Live Demo

View the deployed version of the project here:

[**https://instacloneusingreact.netlify.app/**](https://instacloneusingreact.netlify.app/)

***

## 💡 About

This project is a complete front-end **Instagram clone** built as a Single Page Application (SPA) using the **React** JavaScript library.

The primary objective was to faithfully replicate the visual layout, navigation, and core user experience of Instagram. This serves as a practical demonstration of state management and component-based architecture in a modern web application.

---

## ✨ Functions
* **Story & Post Feed:** Users can view a dynamic main feed that includes simulated **Stories** and **Posts** fetched from a local JSON data source.
* **Profile Navigation:** Clicking on the profile icon navigates the user to a dedicated profile page.
* **User Customization:** Users are able to **change their profile name** and **update their profile picture** on the profile page, showcasing React's ability to manage dynamic user state.

---

## 💻 Tech Stack
* **React:** The main library for building the declarative UI.
* **HTML & CSS:** The foundational languages for application structure and custom styling.
* **Bootstrap:** Utilized for a responsive grid system and pre-styled components.
* **Axios:** A promise-based HTTP client used for fetching data from the mock API.
* **JSON:** Used as the local data source (`db.json`) to simulate a real-world API.
* **React Router DOM:** Essential for handling client-side routing and navigation between views.
---
## 🚀 How to Run the Project (VS Code Terminal)
To successfully run this project.
These commands clone the repository and install all the required packages.
```bash
# Clone the repository
git clone https://github.com/HarinisarathyP/Instagram_clone-using-react
# Navigate into the main project folder
cd Instagram
# Install all main dependencies (from package.json)
npm install
# Install necessary utility packages for data fetching (Axios) and routing (React Router DOM)
npm install axios
npm install react-router-dom
Terminal 1: Start the Mock API Server
npx json-server --watch Instagram\db\db.json --port 3000
# Navigate to the specific React app directory
cd Instagram 
# Start the React development server
npm run dev
