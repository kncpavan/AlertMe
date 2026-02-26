AlertMe – Location Based Smart Alarm System

AlertMe is a smart location-based alarm web application that alerts users when they reach a selected destination radius. Instead of time-based alarms, AlertMe uses real-time geolocation tracking to trigger notifications when the user reaches a predefined location.

This project is useful for travelers, daily commuters, and students who don’t want to miss their stop.

 Features

1)Select start and destination location on map

2)Interactive map using Leaflet.js

Real-time user location tracking (Geolocation API)

4)Alarm triggers when user enters specified radius

5)Customizable radius distance

6)Sound notification alert

7)Responsive UI design

8)Manual latitude & longitude simulation for testing

Tech Stack
Frontend

React.js

HTML5

CSS3

JavaScript

Backend

Node.js

Express.js

Other Technologies

Leaflet.js (Map Integration)

OpenStreetMap API

Browser Geolocation API

How It Works

User selects a destination on the map.

User sets a radius (example: 500 meters).

Application continuously tracks current location.

Distance between current location and destination is calculated using Haversine formula.

If distance ≤ selected radius → Alarm triggers.

Project Structure
AlertMe/
│
├── client/        # React frontend
├── server/        # Node + Express backend
├── package.json
└── README.md
Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/kncpavan/AlertMe.git
cd AlertMe
2️⃣ Install Dependencies

For backend:

cd server
npm install

For frontend:

cd client
npm install
3️⃣ Run the Application

Backend:

npm start

Frontend:

npm start
Future Improvements

Mobile App Version

Push Notifications

User Authentication

Cloud Deployment

Travel History Tracking

Voice Alert System

Use Cases

Bus / Train travel alerts

Daily office commute reminders

Exam center arrival alerts

Tourist location notifications

Author

Knc Pavan
B.Tech CSE – Full Stack Developer Aspirant

Why This Project?

AlertMe solves a real-world problem by combining maps, geolocation, and real-time event triggering, demonstrating strong skills in:

Full Stack Development

API Integration

Real-time location tracking

Problem-solving & system design
