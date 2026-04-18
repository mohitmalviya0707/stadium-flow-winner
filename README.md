# 🏟️ SmartVenue - Stadium Experience Platform

SmartVenue is a real-time, interactive web application designed to enhance the stadium experience for attendees. It provides live crowd density maps, facility wait times, emergency assistance, personalized navigation, accessibility features, and a gamified reward system. The application is built as a Progressive Web App (PWA) for a mobile-first, app-like experience.

---

## ✨ Features

- **📊 Live Crowd Management**: Real-time heatmap of stadium zones with capacity percentages, color-coded density levels (Low, Medium, High, Full), and section-wise capacity bars.
- **⏱️ Real-time Wait Times**: Dynamic updates for entry gates, food & beverage courts, and washroom facilities with color-coded badges.
- **🔔 Smart Alerts**: Real-time system announcements including congestion warnings, match countdowns, facility updates, and emergency notifications.
- **🧭 Intelligent Navigation**: Personalized routes to your seat considering crowd density, distance, and estimated time. Recommends the least crowded path.
- **💺 Interactive Seat Map**: Visual seat picker with availability status (Available, Taken, Your Seat, VIP) and a seat finder search function.
- **🆘 Emergency Assistance**: One-click SOS button that notifies security and medical teams with your location.
- **🎮 Gamification & Rewards**: Earn points by checking in at gates. Redeem points for rewards (e.g., Free Pepsi) using local storage to persist scores.
- **♿ Accessibility First**:
    - Voice-guided navigation using the Web Speech API.
    - Toggleable Colorblind Mode (grayscale + high contrast).
    - Dark/Light mode toggle.
- **📱 PWA Ready**: Includes a service worker registration for offline capabilities and home screen installation.

---

## 🛠️ Technologies Used

- **HTML5**: Semantic structure and content.
- **CSS3**: Modern styling, responsive grid/flex layouts, animations, and dark/colorblind mode themes.
- **JavaScript (ES6+)**: Dynamic data updates, DOM manipulation, real-time clock, local storage, and speech synthesis.
- **Local Storage API**: Persists user reward points across sessions.
- **Web Speech API**: Provides voice navigation for accessibility.
- **Service Workers**: Enables PWA features (offline support, installability).

---

## 🚀 Installation & Setup

No build tools or dependencies are required. This is a pure front-end application.

### Option 1: Direct Download
1.  Download the `index.html` file.
2.  Open the file directly in any modern web browser (Chrome, Firefox, Edge, Safari).

### Option 2: Clone via Git
```bash
git clone https://github.com/your-username/smartvenue-stadium.git
cd smartvenue-stadium
