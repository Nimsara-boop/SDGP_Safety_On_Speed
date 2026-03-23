# Safety On Speed (SOS)

Safety On Speed (SOS) is a modern personal safety application built using React Native. The platform is designed to deliver rapid assistance during emergencies by instantly connecting users with emergency services and trusted contacts.

🔗 Official Website: https://safetyonspeed.lk/

📱 Application Overview

The SOS app is centered around a powerful Emergency Flow system, which automates real-time location sharing and alert notifications to ensure quick response in critical situations.

## 🚨 Key Features
One-Tap SOS Alert
Instantly sends a silent emergency alert with a single tap.
Emergency Flow (Triple Tap Activation)
Initiates a high-priority emergency protocol, including a prompt to contact 119 immediately.
Live Location Tracking & Safety Heatmaps
View an interactive map of Sri Lanka featuring safety heatmaps and quick filters for nearby:
Police Stations
Hospitals
Pharmacies
Guardian Contact System
Add up to five trusted individuals who will receive automatic alerts via SMS and WhatsApp during emergencies.
Safe Spaces Directory
Access important emergency hotlines instantly, including:
Ambulance Services
Fire & Rescue
Women & Child Protection Bureau
Community Forum
A platform where users can discuss safety concerns, share experiences, and raise awareness.
🛠 Installation & Setup (Using Expo)

This project utilizes Expo to enable smooth cross-platform development and testing.

## Prerequisites
Node.js (LTS version recommended)
Expo Go app (Android or iOS)
Supabase account (for backend features, if applicable)

Step 1: Clone and Install
git clone https://github.com/Gagana-Perera/Safety-on-Speed.git
cd safety-on-speed
npm install

Step 2: Environment Configuration

Create a .env file in the root directory and include your required API keys.

Step 3: Run the Application

Start the development server:

npm run start

or

npx expo start

Then:

Open the Expo Go app on your mobile device
Scan the QR code displayed in your terminal
Ensure both devices are connected to the same Wi-Fi network

## 🏗 System Architecture
Frontend: React Native (Expo Managed Workflow)
Styling: NativeWind (Tailwind CSS)
Navigation: React Navigation (Stack & Bottom Tabs)
Maps Integration: Google Maps API with heatmap visualization
Backend: Supabase (Authentication, Database, Real-time services)

## 👥 Development Team
Gagana Perera (Team Lead)
Chamethya Yasodie
Nimsara Karunaratne
Shenal Arosha
Amaya Pitawela
Rivindu Sanjula
