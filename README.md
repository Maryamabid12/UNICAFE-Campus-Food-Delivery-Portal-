# UNICAFE – Campus Food Delivery Portal

A web-based food delivery portal for hostel students to order food from campus cafes and receive delivery to their rooms.

## Problem It Solves

Students in large universities walk 10-15 minutes to reach campus cafes. In summer (45°C), monsoon rains, or late at night, this becomes difficult. During exam weeks, students cannot waste 30-40 minutes walking. UNICAFE brings cafe menus to students' phones and delivers food to hostel rooms.

## Features

- University account login (Student, Cafe Owner, Delivery Boy roles)
- Multi-cafe menu with category filters (Meals, Burgers, Drinks, Snacks, Desserts)
- Cart and checkout with hostel and room number
- Real-time order tracking (accepted → preparing → picked up → delivered)
- Cafe owner dashboard to accept/reject orders and assign delivery boys
- Delivery boy earnings tracker (Rs. 10 tip per delivery)
- Rating system (1–5 stars) and complaint filing

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript (ES6)
- **Backend:** Node.js, Express.js
- **Database:** MySQL 8.0
- **Authentication:** bcrypt password hashing, express-session
- **Version Control:** Git, GitHub
- **Project Management:** Trello (Scrum board)

## Project Structure

UNICAFE/
├── public/
│ ├── css/
│ ├── js/
│ └── images/
├── views/
│ ├── login.html
│ ├── register.html
│ ├── student-dashboard.html
│ ├── cafe-owner-dashboard.html
│ └── delivery-dashboard.html
├── routes/
├── controllers/
├── models/
├── config/
├── .env
└── server.js
