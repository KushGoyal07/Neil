# StayNest 🏡

StayNest is a full-stack accommodation booking platform that allows users to explore, list, and book stays with a seamless and secure experience. Built using **HTML**, **CSS**, **JavaScript**, **Node.js**, **Express**, and **MongoDB**, StayNest combines robust backend services with a user-friendly frontend.

## 🌟 Features

- 🔐 **User Authentication** – Secure sign-up and login system using Passport.js and `passport-local-mongoose`.
- 🏘️ **Property Listings CRUD** – Hosts can create, edit, and delete their accommodation listings.
- 📅 **Booking Functionality** – Guests can book stays and manage their bookings.
- ✍️ **Review System** – Users can leave reviews for properties they have stayed in.
- 🗺️ **Mapbox Integration** – Interactive maps to display property locations.
- 🌐 **Responsive Design** – Fully mobile-friendly interface.
- 📦 **RESTful API** – Clean and scalable API design.
- ☁️ **MongoDB Atlas** – Cloud database support for scalability and reliability.
- 🚀 **Deployment** – Deployed on Render with continuous integration and delivery support.
- 🧠 **MVC Architecture** – Organized codebase following the Model-View-Controller pattern.

## 📸 Demo

> 🔗 [Live Demo (Render)](https://staynest-ksc4.onrender.com/)  



## 🛠️ Tech Stack

| Tech             | Purpose                          |
|------------------|----------------------------------|
| HTML/CSS/JS      | Frontend UI                      |
| Node.js          | Runtime Environment              |
| Express.js       | Backend Framework                |
| MongoDB + Atlas  | Database & Cloud Storage         |
| Passport.js      | Authentication & Authorization   |
| Mapbox API       | Maps Integration                 |
| EJS              | Templating Engine (if used)      |
| Render           | Deployment Platform              |

## 🚀 Getting Started

### Prerequisites

- Node.js & npm installed
- MongoDB Atlas account (or local MongoDB)
- Mapbox API key

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/GAUTAMGUPTA0004/StayNest.git
   cd StayNest
Install dependencies:

bash
Copy
Edit
npm install



bash
Copy
Edit
npm start
Visit http://localhost:8080 in your browser.

🔐 Authentication & Roles
Users can sign up as hosts or guests.

Hosts can list, update, or remove properties.

Guests can search listings and make bookings.

Authentication is handled securely using passport-local-mongoose.

📁 Project Structure
bash
Copy
Edit
StayNest/
├── models/
├── routes/
├── views/
├── public/
├── controllers/
├── app.js
├── .env.example
└── README.md
📌 Future Improvements
Add payment integration (e.g., Stripe)

Implement messaging between host and guest

Add wishlist functionality

📝 License
This project is licensed under the MIT License – see the LICENSE file for details.

🙌 Acknowledgements
Mapbox

MongoDB Atlas

Render

Passport.js

👨‍💻 Author
Gautam Gupta
🔗 GitHub
