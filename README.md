# 🌿 EcoSort 

**[😎 Click Here to Try the Live Demo!](https://eco-sort-mu.vercel.app/)**

>>>>>>>>>EcoSort is a smart, web-based waste classification and routing system designed to promote a "Green Campus" environment. By leveraging on-device machine learning, it helps students and staff instantly identify waste types and directs them to the nearest appropriate disposal bin.

---

## Problem Statement
**Category: Open Innovation**

Improper waste segregation on educational campuses leads to inefficient recycling and increased environmental footprint. Students and staff often struggle to identify which bin (e.g., Paper/Plastic, Metal/Glass, Organic) is appropriate for their waste, or they do not know where the nearest proper bin is located. EcoSort AI tackles this by providing real-time AI classification and mapping.

---

## About the Project (Green Campus Initiative)
EcoSort AI acts as a digital sustainability assistant. Users simply point their device's camera at a piece of waste. The application uses a pre-trained neural network (TensorFlow.js MobileNet) right in the browser to classify the item. Based on the classification, it maps the user to the nearest correct dustbin on campus using an interactive map.

### Current Features
* **Real-Time AI Scanning:** Uses the device's camera to analyze waste in real-time.
* **Instant Classification:** Categorizes waste into predefined buckets (Organic, Plastic/Paper, Metal/Glass).
* **Smart Routing:** Calculates the distance to campus bins and directs the user to the nearest correct one.
* **Interactive Campus Map:** Visualizes the user's location and the target bin using Leaflet.js.
* **Fully Client-Side:** Runs entirely in the browser without needing a backend server for image processing.

---

## 🛠️ Tech Stack
* **Frontend:** HTML5, Tailwind CSS, CSS Animations
* **Machine Learning:** TensorFlow.js, MobileNet v2
* **Mapping & Geolocation:** Leaflet.js, OpenStreetMap
* **Deployment:** Can be hosted on any static site provider (GitHub Pages, Vercel, Netlify)

---

## 🔮 Future Developments
Our roadmap for taking EcoSort AI to the next level includes:
* **Enhanced AI Accuracy & Categories:** Transitioning from a generic model to a custom-trained AI model specifically optimized for Indian campus waste, adding more granular categories (e.g., E-waste, Hazardous).
* **User Authentication:** Implementing a secure student/staff login system.
* **Personalized Dashboards:** Creating user profiles to track individual recycling habits and overall campus impact.
* **Gamification & Rewards:** Introducing a point-based system where students earn reward points for consistently contributing to the green campus initiative by sorting waste correctly.
* **Live GPS Tracking:** Replacing static coordinates with the HTML5 Geolocation API for real-time user tracking.

---

## 👥 Our Team
* **Adarsh M** (USN: 1VA23IS002) 
* **Kavana H** (USN: 1VA23IS045)
* **Janani V** (USN: 1VA23IS038)
* **Shreya P Shetty** (USN: 1VA23IS099)

---

## ⚙️ How to Run Locally
1. Clone this repository to your local machine.
2. Open the project folder.
3. Open the `index.html` file in any modern web browser (Chrome, Firefox, Safari).
   * *Note: Camera access requires the site to be served over `https://` or `localhost`. If running locally, you can use an extension like VS Code Live Server.*

![PokemonThankyouGIF](https://github.com/user-attachments/assets/221964d6-08a2-406f-bf7e-0b5e13cbfca9)
