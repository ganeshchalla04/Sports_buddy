Sports Buddy Web App

**Sports Buddy** is a dynamic web application that connects users based on their shared interest in sports. Users can submit and browse nearby sports events, find sports buddies, and build connections beyond their social circles.

---

  🚀 Features
- User-friendly interface with colorful UI
- Add sports activity details: sport, skill level, time, and location
- View a live list of upcoming matches
- Integrated with Firebase Firestore for real-time data storage and retrieval

---

  🛠️ Technologies Used
- **HTML5**
- **CSS3** (with modern styling and layout)
- **JavaScript (ES6)**
- **Firebase Firestore (NoSQL Database)**

---

  📦 Setup Instructions

1. **Clone the repository**
```bash
https://github.com/your-username/sports-buddy.git
```

2. **Open the project folder**
```bash
cd sports-buddy
```

3. **Add Firebase Config**
Replace the Firebase configuration in the `<script>` section of the `index.html` file with your Firebase project credentials:
```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT_ID.appspot.com",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

4. **Open `index.html` in your browser**
You can double-click the file or use a local server such as Live Server in VS Code.

---

  📁 File Structure
```
/your-project-folder
├── index.html         # Main app structure
├── style.css          # (Optional if you separate styles)
├── app.js             # (Optional if you separate JS)
├── README.md          # Project documentation
```

---

  🧠 Future Improvements
- User authentication with Firebase Auth
- Filtering events by location/sport
- Responsive mobile design
- Profile pages and chat feature

---

  📄 License
This project is open source and available under the [MIT License](LICENSE).

---

  💬 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
