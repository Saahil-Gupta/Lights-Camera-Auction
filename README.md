# 🎬 Lights Camera Auction

**Lights Camera Auction** is a silent auction web application built with React and Flask, designed to allow users to place timed bids on items in real time. The project simulates an auction event where users can register, view listings, and bid before the timer runs out—without knowing other users' bids.

---

## 🌟 Features

- 🔒 **User Registration/Login**  
  Secure authentication using JWTs for protected routes.

- ⏰ **Timed Auctions**  
  Each item has a countdown timer that closes bidding once time is up.

- 🪄 **Silent Bidding**  
  Users place bids privately—other users can't see the highest bid until the auction ends.

- 🔔 **Webhook-based Updates**  
  Auction data syncs automatically using webhooks and backend polling.

- 📦 **Responsive Frontend**  
  Built using React with a sleek, mobile-friendly UI.

---

## 🛠 Tech Stack

**Frontend**  
- React  
- Axios  
- React Router

**Backend**  
- Flask  
- Flask-JWT  
- SQLite (can be upgraded to PostgreSQL/MySQL)

**Others**  
- Webhooks for triggering bid updates  
- Bootstrap for styling

---

## 🚀 Getting Started

### Prerequisites

- Node.js
- Python 3.x
- pip (Python package manager)

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

### Backend Setup

```bash 
cd auction-backend
pip install -r requirements.txt
python server.py
python client.py
python client2.py
```
(If you want to emulate bidding)

