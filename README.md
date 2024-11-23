# Netflix Clone 🎥

A Netflix-inspired web application that allows users to browse and view details of movies and TV shows based on genres. Built using **React**, **Firebase**, **Axios**, and the **TMDB API**, this project provides an interactive experience for users to explore entertainment content.

---

## Features 🌟

- **Browse Movies & TV Shows:** Displays various genres, trending shows, and more.
- **Responsive Design:** Seamless viewing experience across devices.
- **Firebase Integration:** User authentication (Sign up, Sign in).
- **TMDB API:** Fetch real-time data for movies and series.
- **Axios:** Simplified API requests.
- **Dynamic Routing:** Navigate to pages for specific movie details.
- **Favorites Feature:**
  - **Add to Favorites:** Users can save their favorite movies and series.
  - **Favorites Page:** A dedicated page to view all saved favorite items.

---

## Demo 🚀

https://netflix-fc04b.web.app/

---

## Getting Started 🛠️

Follow these steps to set up and run the project locally:

### Prerequisites

Make sure you have the following installed:

1. **Node.js**: [Download and install Node.js](https://nodejs.org/).
2. **npm** or **yarn**: Comes with Node.js, used for managing packages.
3. **Git**: [Download Git](https://git-scm.com/) to clone the repository.
4. **TMDB API Key**: Sign up at [TMDB](https://www.themoviedb.org/) to get your API key.
5. **Firebase Account**: Create a project in Firebase to set up authentication and Firestore.

---

## Installation 📦

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/netflix-clone.git
cd netflix-clone

```
### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Firebase

- Go to your Firebase console and create a project.
- Enable Authentication and set up Email/Password authentication.
- Enable Firestore Database for storing user data (e.g., favorite movies).
- Copy the Firebase config object from the Firebase settings.
- Create a .env file in the root of your project and add your Firebase configuration:

```bash
REACT_APP_FIREBASE_API_KEY=your-api-key  
REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain  
REACT_APP_FIREBASE_PROJECT_ID=your-project-id  
REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket  
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-sender-id  
REACT_APP_FIREBASE_APP_ID=your-app-id  
```

### 4. Configure TMDB API
- Go to [TMDB](https://www.themoviedb.org/) and sign up/log in.
- Generate your API key from the API settings.
- Add your TMDB API key to the .env file:

```bash
REACT_APP_TMDB_API_KEY=your-tmdb-api-key
```
### 5. Start the Development Server

Run the following command:

```bash
npm start  
```
---
## Scripts 📜

### Start Development Server:

```bash
npm start
```
### Build for Production:

```bash
npm run build  
```
