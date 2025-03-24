# 📍 OpenStreetMap Route Finder (with FlutterFlow & Node.js)

A web-based route finder that allows users to search for addresses and find optimal routes using **OpenStreetMap**, **Leaflet.js**, and **OSRM**. Integrated with **FlutterFlow** for seamless use in mobile applications, with a **Node.js (Express) backend** for geocoding and route planning.

---

## 🌍 Demo  
![Route Finder](screenshot.png) *(Replace with an actual screenshot or GIF)*  

🚀 **[Live Demo](https://your-live-demo-link.com)** *(If available)*  

---

## 🚀 Features  
✅ **Address Search:** Enter start and destination locations to find routes.  
✅ **Real-Time Route Calculation:** Uses OpenStreetMap and OSRM to generate optimal routes.  
✅ **Custom Route Colors:** Choose from multiple colors (blue, red, green, etc.).  
✅ **Browser Geolocation:** Automatically sets the initial map view to the user's location.  
✅ **FlutterFlow Integration:** Embedded via WebView for seamless mobile use.  
✅ **Node.js Backend:** Handles geocoding and route planning requests.  
✅ **Error Handling:** Alerts for invalid addresses, missing input, or failed route fetches.  

---

## 🛠️ Tech Stack  

### **Frontend:**  
- **HTML, CSS, JavaScript** (for web interface)  
- **Leaflet.js** (for map rendering & route visualization)  
- **OpenStreetMap** (for geocoding & mapping)  
- **FlutterFlow WebView** (to embed in Flutter app)  

### **Backend:**  
- **Node.js + Express.js** (for handling geocoding & routing requests)  
- **Render** (for backend deployment)  

### **APIs Used:**  
- **Nominatim API** – Converts addresses to latitude/longitude  
- **OSRM API** – Calculates routes between two locations  

---

## 🔧 How to Run Locally  

### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
