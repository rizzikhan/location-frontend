# 📱 Frontend - Location Tracker

## 🚀 Project Overview

This is the frontend for the Location Tracker application. It allows users to interact with a simple interface that captures their geolocation when they click a button.

## 🛠️ Technologies Used

- **HTML**: Structure of the web page.
- **CSS**: Styling for the user interface.
- **JavaScript**: To capture geolocation and send it to the backend.
- **Vercel**: For hosting and deployment.

---

## 📂 Folder Structure

```
location-frontend/
├── index.html          # Main HTML file
├── style.css           # Stylesheet for UI design
└── background.jpg       # Background image (optional)
```

---

## ⚙️ Installation and Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/location-frontend.git
   cd location-frontend
   ```

2. **Open `index.html` in a Browser:**

   - Simply double-click the `index.html` file or serve it with a local server:
     ```bash
     npx serve
     ```

3. **Connect to Backend:**

   - Ensure the `fetch()` URL in the `index.html` points to the correct backend URL.

4. **Deploy on Vercel:**
   ```bash
   vercel --prod
   ```

---

## 🚀 How It Works

- Displays a simple UI asking "Are you above 18?" with a button.
- On clicking "Yes," the browser requests location access.
- If permission is granted, the geolocation is sent to the backend API.

---

## 🌍 API Endpoint

The frontend communicates with the backend using this endpoint:

```javascript
fetch("https://your-backend.vercel.app/location", { method: "POST" });
```

Make sure to replace the URL with your backend's deployed URL.

---

## 🤝 Contribution

Feel free to fork the repo, make changes, and submit pull requests.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
