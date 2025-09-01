# Joke-Generator-2.0

A fun little web project where you enter your **name** and **mood**, and the app provides you with random jokes.  
Built with **HTML, CSS, and JavaScript**.  

---

## ✨ Features
- 🎭 Takes **your name** and **current mood** as input.  
- 😂 Generates a **random joke** every time you click **Get Joke**.  
- 🔄 Click **New Joke** to get a fresh one instantly (25 total jokes available).  
- 🎨 Simple and clean UI, beginner-friendly.  
- 🖥️ Runs directly in the browser — no server setup needed.  

---

## ⚙️ How It Works
1. Open the app in your browser.  
2. Enter your **name** and select your **mood**.  
3. Click **Get Joke** → A joke appears based on your input.  
4. Click **New Joke** → Instantly fetches another random joke.  

---

## 🧑‍💻 Code Explanation
- **index.html**  
  - Contains input fields for name and mood.  
  - Buttons for **Get Joke** and **New Joke**.  
  - A section to display jokes dynamically.  

- **style.css**  
  - Adds colors, fonts, spacing, and button styles.  
  - Makes the app look neat and modern.  

- **script.js**  
  - Stores **25 jokes** in an array.  
  - Fetches a random joke using `Math.random()`.  
  - Updates the DOM (`document.getElementById(...)`) to show the joke.  
  - Handles button clicks for smooth user experience.  

---

🤝 Contribution
Pull requests are welcome! If you have better jokes or styling ideas, fork this repo and submit a PR.
