# TrackFlow Prototype

A real-time delivery tracking prototype built using Socket.IO, live geolocation, and interactive maps.

This project was created as the foundation for a larger delivery tracking system for real business operations, where:
- Customers can track delivery partners live
- Delivery managers can monitor all active delivery partners
- Delivery partners can share live location updates

---

# Features

- Real-time live location tracking
- WebSocket communication using Socket.IO
- Interactive map integration
- Dynamic marker updates
- Multi-user tracking
- Automatic disconnect handling

---

# Tech Stack

## Frontend
- HTML
- CSS
- JavaScript
- Leaflet.js

## Backend
- Node.js
- Express.js
- Socket.IO

---

# How It Works

1. User shares live location using browser geolocation
2. Coordinates are sent to the server using Socket.IO
3. Server broadcasts updated coordinates
4. Connected clients receive live updates
5. Marker positions update in real time on the map

---

# Future Improvements

- Delivery partner authentication
- Customer tracking portal
- Admin dashboard
- Role-based access control
- MongoDB integration
- Order management system
- Route optimization
- ETA calculation
- Mobile responsiveness
- Production deployment

---

# Project Status

This repository contains the initial prototype version.

A new scalable production architecture will be developed separately.

---

# Author

Raj Singh
