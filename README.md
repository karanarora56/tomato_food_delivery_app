# 🍅 Tomato: A Food Delivery App

**Live Demo Links:**  
- [Customer Interface (Frontend)](https://tomato-food-delivery-app-frontend-qtn9.onrender.com)  
- [Admin Panel](https://tomato-food-delivery-app-admin-m805.onrender.com)  
- [Backend API](https://tomato-food-delivery-app-backend-gqgj.onrender.com)

---

**Tomato** is a full-featured, responsive food delivery application built using the **MERN stack** (MongoDB, Express, React, Node.js) with **Stripe payment integration**. This project delivers a seamless experience for customers, administrators, and delivery personnel, combining a user-friendly frontend, a robust backend, and an intuitive admin panel into a single, comprehensive platform.

---

## 🚀 Features

### 👨‍🍳 Customer Interface (Frontend)
- **Responsive Design:** Developed with React, Tomato offers a fully responsive interface that adapts to various devices, from desktops to mobile screens, ensuring an optimized user experience.
- **User Authentication:** Secure user login and registration using JSON Web Tokens (JWT) to manage sessions and protect user data.
- **Browse and Search:** Users can browse restaurants, view menus, and search for food items by category, popularity, or dietary preference.
- **Order Management:** Customers can place orders, select their preferred delivery address, and track the status of their orders in real-time.
- **Payment Integration:** With Stripe integrated, users can make secure, hassle-free payments directly within the app.

### 🛠️ Admin Panel
- **User Management:** Admins can view and manage user accounts, including customer and delivery personnel information.
- **Menu and Restaurant Management:** Easily add, edit, and delete food items, categories, and restaurant details to keep the offerings up to date.
- **Order Tracking:** Real-time monitoring of active and past orders, with controls to update the order status (e.g., received, in-progress, completed, delivered).
- **Analytics:** Track key metrics like popular items, order frequency, and user activity to make informed decisions and improve services.

### ⚙️ Backend (Server)
- **API Development:** Built with Express, the backend provides RESTful APIs to handle requests, manage authentication, and connect the frontend and admin panel to the MongoDB database.
- **Data Storage:** MongoDB is used for storing user profiles, order details, restaurant data, and menu items in a scalable and efficient manner.
- **Real-Time Updates:** With WebSockets, users receive live updates on their order status from the moment they place it until delivery.
- **Security:** Data protection and secure endpoints, with encrypted user information and secure payment processing via Stripe.

---

## 🧱 Technology Stack

| Layer        | Technology                         |
|--------------|------------------------------------|
| Frontend     | React, CSS3, Bootstrap/Material UI |
| Backend      | Node.js, Express.js                |
| Database     | MongoDB                            |
| Real-Time    | WebSockets (Socket.IO)             |
| Authentication | JWT                              |
| Payments     | Stripe                             |
| Deployment   | Render                             |

---

## 🛠 Getting Started

To get started with this project, follow these steps:

### 📁 Clone the Repository

```bash
git clone <your-repo-url>

### 📦 Install Dependencies

```bash
# Client
cd client
npm install

# Server
cd ../server
npm install

# Admin
cd ../admin
npm install
```

### 🔐 Set Up Environment Variables

Create a `.env` file in the `server/` directory with the following keys:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

### ▶️ Run the Application

```bash
# Start the client
cd client
npm start

# Start the server
cd ../server
npm start

# Start the admin panel
cd ../admin
npm start
```

> Make sure MongoDB and Stripe credentials are valid for full functionality.

---

## 📁 Project Structure

```bash
Tomato/
│
├── client/                  # Frontend code (React)
│   ├── public/
│   ├── src/
│       ├── components/
│       ├── pages/
│       └── utils/
│
├── server/                  # Backend code (Node.js, Express)
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── middleware/
│
├── admin/                   # Admin panel (React, can be separate or part of client)
│   ├── components/
│   └── pages/
│
├── .env                     # Environment variables
├── README.md
└── package.json
```

---

## 🌟 Future Enhancements

- 🔔 **Push Notifications:** Notify users about order updates and special offers.
- 📊 **Advanced Analytics:** Provide deeper insights for restaurant and admin users.
- 🌐 **Multi-Language Support:** Make the app accessible to a broader audience by adding multiple languages.
- 📍 **Live Location Tracking:** Integrate delivery partner tracking for real-time map updates.

---

## 🤝 Contribution Guidelines

We welcome contributions from the community! Here's how to contribute:

1. **Fork** this repository.
2. **Clone** your fork:
   ```bash
   git clone https://github.com/your-username/tomato.git
   ```
3. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
4. Make your changes.
5. Commit and push:
   ```bash
   git add .
   git commit -m "Add feature"
   git push origin feature-name
   ```
6. Submit a **Pull Request**.

> Please make sure to follow standard coding practices and add meaningful comments to your code.

---

## 📬 Contact

If you have any questions or suggestions, feel free to [open an issue](https://github.com/your-username/tomato/issues) or connect with the maintainer.

---

**Enjoy exploring the Tomato codebase and feel free to share your feedback!**
