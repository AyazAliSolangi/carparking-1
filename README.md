# SmartPark - Intelligent Parking Management System

> A web-based solution designed to streamline parking operations and reservations with enhanced monitoring features.

## 📋 Table of Contents
- [Overview](#overview)
- [Key Functionalities](#key-functionalities)
- [Technology Stack](#technology-stack)
- [Core Logic](#core-logic)
- [How to Use](#how-to-use)
- [Contributions](#contributions)
- [License](#license)

## 🧩 Overview
**SmartPark** is an intelligent system that simplifies the management of vehicle parking spaces. It offers an organized interface for both administrators and users to handle bookings, monitor parking durations, and maintain space availability with ease. Whether it's a small parking lot or a multi-level parking facility, this system boosts operational efficiency and user experience.

## ✨ Key Functionalities
- Clean and responsive user interface
- Secure login and registration for users and admins
- Dynamic space allocation with create, update, and delete options
- Booking system with availability tracking
- Built-in timer to monitor parked duration
- Real-time updates of occupied and vacant spaces

## 💻 Technology Stack
- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** PHP, Python (Flask), MySQL
- **Libraries & Tools:** Bootstrap 5, jQuery

## ⚙️ Core Logic
The application employs a **priority queue (heap)** structure to manage and assign parking slots efficiently. Empty slots are organized based on how close they are to the entrance. When a user initiates a booking, the nearest available spot is selected first. This reduces walking time and maximizes lot usage.

The logic ensures:
- Fast retrieval of nearest spaces
- Balanced slot assignment
- Reduced user waiting time

## 🚀 How to Use
1. Launch the system in your preferred web browser.
2. Create an admin account for managing parking lots and viewing usage analytics.
3. Users can register to view and reserve slots.
4. Book a space, start the timer, and track your parking duration in real time.

## 🤝 Contributions
We welcome all ideas, fixes, and features that could enhance this platform. To contribute:
- Fork the repository
- Make your changes
- Open a pull request

## 📄 License
This software is distributed under the terms of the [MIT License](https://opensource.org/licenses/MIT).

---

**Developed with 💡 by Ayaz Ali**

