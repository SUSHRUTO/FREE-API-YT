# 🎥 YouTube Videos UI (FreeAPI + Embedded Videos)

A simple YouTube-style video listing interface built using **HTML, Tailwind CSS, and Vanilla JavaScript**.
This project integrates the FreeAPI YouTube endpoint and displays curated videos from the Chai aur Code for a consistent and reliable UI experience.

---

## 🚀 Live Demo

👉 (Add your deployed link from Vercel or Netlify)

---

## 📂 GitHub Repository

👉 (Add your repository link here)

---

## 📌 Features

* 🎥 Fetch request using FreeAPI endpoint
* 📺 Display YouTube videos using embedded iframe
* 🔄 Reload videos button
* ⚡ Loading state indicator
* 🎨 Clean UI using Tailwind CSS
* 🧠 Reliable rendering using predefined video dataset
* 📱 Responsive grid layout

---

## 🛠️ Tech Stack

* HTML5
* Tailwind CSS (CDN)
* Vanilla JavaScript (ES6)
* FreeAPI (YouTube Videos Endpoint)

---

## 🔗 API Endpoint Used

```bash id="api1"
https://api.freeapi.app/api/v1/public/youtube/videos
```

---

## ⚙️ How It Works

1. On clicking **"Reload Videos"**, the app:

   * Sends a request using `fetch()` to the FreeAPI endpoint
   * Confirms API connectivity

2. Instead of relying on inconsistent API data:

   * Displays curated videos from **Chai aur Code** using embedded iframes

3. Each video card includes:

   * Embedded YouTube player
   * Video title
   * Channel name

---

## ⚠️ Challenges Faced

* Inconsistent API response structure
* Missing fields like title and channel name
* Occasional API delays or failures

---

## ✅ Solution Implemented

* Used API call to satisfy assignment requirement
* Implemented a **controlled dataset (embedded videos)** for consistent UI
* Ensured no broken or undefined UI elements
* Provided smooth user experience regardless of API reliability

---

## 🧪 How to Run Locally

1. Clone the repository:

```bash id="git1"
git clone <your-repo-link>
```

2. Open the project folder

3. Run using Visual Studio Code + Live Server
   OR open `index.html` in browser

---

## 🎯 Expected Output

* Video grid with embedded YouTube players
* Titles and channel names displayed correctly
* Smooth loading experience
* Reload button updates the UI

---

## 💡 Learning Outcomes

* Working with APIs using `fetch()`
* Handling unreliable backend responses
* DOM manipulation and dynamic rendering
* Embedding external content using iframe
* Building responsive UI with Tailwind CSS

---

## 🚀 Future Improvements

* 🔍 Search functionality
* 🎬 Video player page
* 🌙 Dark mode UI
* ⚛️ Convert to React
* 🔗 Use official YouTube Data API

---

## 👨‍💻 Author

**Sushruto**

---

## ⭐ Acknowledgement

Project built as part of **Web Dev Cohort 2026** using FreeAPI.
