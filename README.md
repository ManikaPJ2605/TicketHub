## 📄 `README.md` – TicketHub 🎟️


# 🎟️ TicketHub

TicketHub is a simple movie ticket booking web application built with **Node.js**, **Express**, and **MongoDB**. It allows users to select a movie, choose a time slot, and book tickets. The bookings are stored in a MongoDB Atlas database.

---

## 🌐 Live Demo

> 🚀 Hosted on Render: https://tickethub-smea.onrender.com 


---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas
- **Frontend**: HTML, CSS (Basic UI)
- **Hosting**: Render

---

## 📁 Folder Structure

```

TicketHub/
├── public/               # Frontend HTML, CSS
│   ├── index.html
│   └── styles.css
├── server.js             # Main backend server
├── models/
│   └── Booking.js        # Mongoose model for bookings
├── .env                  # MongoDB connection string (keep secret)
├── package.json          # Project metadata & dependencies
└── README.md             # Project documentation

````

---

## 📦 Installation & Setup (Local)

1. **Clone the repository**
   ```bash
   git clone https://github.com/ManikaPJ2605/TicketHub.git
   cd TicketHub
````

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Create a `.env` file**

   ```env
   MONGO_URI=your_mongodb_connection_url
   ```

4. **Start the server**

   ```bash
   npm start
   ```

5. Open your browser and visit:
   [http://localhost:3000](http://localhost:3000)

---

## ☁️ Deploying on Render

1. Push the project to GitHub
2. Go to [https://render.com](https://render.com) → New Web Service
3. Connect your GitHub repo
4. Set:

   * Build Command: `npm install`
   * Start Command: `npm start`
   * Runtime: Node
5. Add your environment variable:

   ```
   MONGO_URI=your_mongo_url
   ```
6. Deploy and wait for it to go live 🎉

---

## 🧠 Features

* Simple movie ticket booking form
* Stores user bookings to MongoDB
* Express-based routing and form handling
* Deployed and live on the web


