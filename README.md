# everwardtours.com.ai
# EVERWARD Ecosystem (v1.0.0)

## 🌐 The Master Vision
**EVERWARD** is a context-aware travel operating system designed for the modern **Global Citizen**. Operated by **Global Citizen Joe LLC (Philadelphia, PA)**, the ecosystem bridges the gap between digital logistics, global booking, and physical security.

Our mission is to move travelers **Everywhere Forward** by providing an assistant that adapts in real-time to their mode of transport.

---

## 🏗 Project Architecture
This repository contains the monorepo for the three primary pillars of the brand:

1.  **EverwardTours.com**: A high-performance global booking engine (Hotels, Flights, Rentals) utilizing industry-leading Travel APIs.
2.  **Everward.app**: A Progressive Web App (PWA) "Live Assistant" that switches UI based on GPS speed and location.
3.  **Citizen Defense & Risk**: The security-focused API layer providing risk assessment and "Safe-Zone" data for high-risk travel.

---

## 🛠 Tech Stack
* **Frontend:** Next.js 15+ (React)
* **Mobile:** React Native (Expo)
* **Maps:** Mapbox GL JS (Customized with the "Unbroken Compass" UI)
* **Data Sources:** Priceline, Amadeus, and Expedia Partner APIs

---

## ⚡ The "Context-Switcher" Logic
| Mode | Trigger (Speed/GPS) | Key Features |
| :--- | :--- | :--- |
| **Pedestrian** | < 5 mph | AR Arrows, Smoking Zones, Safe-Walk Corridors. |
| **Transit** | 15 - 80 mph (Rail) | Stop Alerts (Haptic), Station Maps. |
| **Flyer** | Geofence (Airport) | Gate Navigation, Ground-Prep Caching. |
| **Driver** | 5 - 85 mph (Roads) | Parking Entrances, Pit-Stop Planning. |

---

## 🛡 Security & Risk (Citizen Defense & Risk)
Everward integrates physical safety into the digital experience:
* **Safe-Walk Corridors:** Pedestrian routes filtered by lighting and local safety data.
* **Risk Overlays:** Real-time "Green/Yellow/Red" zone mapping.

---

## ⚖ Legal & Compliance
**EverwardTours.com** and **Citizen Defense & Risk** are DBAs of **Global Citizen Joe LLC**. 
* **Registered Office:** Philadelphia, Pennsylvania.

---
> **"Moving you Everywhere Forward."**
everwardtours.com The official home for EVERWARD.APP and EVERWARDTOURS.COM. A context-aware travel assistant and global booking engine for the modern Global Citizen. Built under Global Citizen Joe LLC.
EVERWARD Ecosystem (v1.0.0)🌐 The Master VisionEVERWARD is a context-aware travel operating system designed for the modern Global Citizen. Operated by Global Citizen Joe LLC (Philadelphia, PA), the ecosystem bridges the gap between digital logistics, global booking, and physical security.Our mission is to move travelers Everywhere Forward by providing an assistant that adapts in real-time to their mode of transport.🏗 Project ArchitectureThis repository contains the monorepo for the three primary pillars of the brand:EverwardTours.com: A high-performance global booking engine (Hotels, Flights, Rentals) utilizing industry-leading Travel APIs.Everward.app: A Progressive Web App (PWA) "Live Assistant" that switches UI based on GPS speed and location.Citizen Defense & Risk: The security-focused API layer providing risk assessment and "Safe-Zone" data for high-risk travel.🛠 Tech StackFrontend: Next.js 15+ (React)Mobile: React Native (for cross-platform mobile parity)Styling: Tailwind CSS (Modern, responsive, mobile-first)Backend: Node.js / ExpressDatabase: MongoDB Atlas (User Blueprints & Favorite Spots)APIs: * Stays/Cars: Priceline/Expedia Partner NetworksFlights: Amadeus Self-Service APIMaps: Mapbox GL JS (Customized with the "Unbroken Compass" UI)⚡ The "Context-Switcher" LogicThe core differentiator of Everward is its ability to detect travel modes and update the UI accordingly.Mode Configurations:ModeTrigger (Speed/GPS)Key FeaturesPedestrian< 5 mphAR Walking Arrows, Smoking Zones, Restroom Finder, Elevator Access.Transit15 - 80 mph (Rail/Bus)Stop Alerts (Haptic), Station Interior Maps, Transfer Logistics.FlyerGeofence (Airport)Gate-to-Gate Navigation, Lounge Access, "Ground-Prep" caching.Driver5 - 85 mph (Roads)Parking Entrance GPS, Pit-Stop Planning, EV/Gas stations.🛡 Security & Risk (Citizen Defense & Risk)Everward integrates physical safety into the digital experience:Safe-Walk Corridors: Pedestrian routes filtered by lighting and local safety data.Risk Overlays: Real-time "Green/Yellow/Red" zone mapping for international travelers.Emergency Node: One-tap connection to Citizen Defense & Risk tactical support (Private Executive Protection).🚀 Getting Started1. InstallationBashgit clone https://github.com/your-username/everward-ecosystem.git
cd everward-ecosystem
npm install
2. Environment VariablesYou will need to create a .env file with the following keys:AMADEUS_API_KEY: (For Flights)PRICELINE_PARTNER_ID: (For EverwardTours.com)MAPBOX_ACCESS_TOKEN: (For the Unbroken Compass GPS interface)⚖ Legal & ComplianceEverwardTours.com and Citizen Defense & Risk operate as DBAs of Global Citizen Joe LLC.Registered Office: Philadelphia, Pennsylvania.Compliance: This software is designed to comply with Pennsylvania Fictitious Name Act and Seller of Travel (SOT) consultation frameworks.📧 Contact & SupportFounder: Global Citizen JoeDigital Hub: everward.appBooking Hub: everwardtours.com"Moving you Everywhere Forward."
