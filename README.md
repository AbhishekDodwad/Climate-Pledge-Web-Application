# 🌱 Climate Action Pledge Microsite

A responsive single-page website built to inspire and track climate action by allowing individuals to:

- ✅ Take a voluntary climate pledge  
- ✍️ Record their sustainability commitments  
- 🧾 Instantly receive a personalized certificate  
- 🧑‍🤝‍🧑 Be featured on a public pledge wall  
- 📊 View live community impact metrics  

---

## 🔗 Live Demo

🌍 **Live Site:** [Your Live Link Here]([https://your-deployment-link.netlify.app](https://abhishekdodwad.github.io/Climate-Pledge-Web-Application/))  
📁 **Source Code:** [GitHub Repository](https://github.com/AbhishekDodwad/Climate-Pledge-Web-Application)

---

## 🧩 Features

### 🎯 Hero Section
- Motivational banner with a clear climate call-to-action
- "Take the Pledge" button with smooth scroll to form

### 📊 Live KPIs
- Dynamic counters for:
  - Total pledges (simulated from backend + base number)
  - Daily average
  - Community goal progress (target: 1,000,000)
  - Profile distribution: Students, Professionals, Others

### 🌍 Why Take Climate Action
- Highlights the importance of individual action
- Bite-sized facts with icons to build awareness

### ✍️ Pledge Form
- Fields: Full Name, Email, Mobile, State, Profile
- 9 total commitments under 3 themes (min 3 required)
- Validation for completeness and accuracy

### 🧾 Certificate Generator
- Instant personalized certificate upon form submission
- Includes:
  - User's name
  - Number of commitments
  - Rating (1–5 stars)
  - Date of pledge
  - Motivational message
- Options to **Print** and **Share**

### 🌟 Pledge Wall
- Displays pledge info: Name, State, Profile, Date, Commitments, Rating
- Pledge data fetched from Google Sheets
- "Load More" functionality for scrolling

### 🔐 Privacy First
- Email and mobile are **required** but **never shown**
- Used only for backend validation
- Privacy note displayed clearly on the form and footer

---

## 🧠 Tech Stack

| Frontend                    | Backend (Mock)           | Deployment     |
|-----------------------------|--------------------------|----------------|
| HTML5, TailwindCSS, JS      | Google Apps Script + Sheets | GitHub Pages |

---

## 🚀 Getting Started

```bash
# 1. Clone this repo
git clone https://github.com/YourUsername/Climate-Pledge-WebApp.git

# 2. Open in your code editor or simply open index.html in browser
cd Climate-Pledge-WebApp
