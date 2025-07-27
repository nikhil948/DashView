# DashView
📊 Real-Time Data Pipeline & Dashboard

A full-stack MERN project that simulates real-time data ingestion using Redis Streams (or Kafka), processes it with Node.js, stores it in MongoDB, and visualizes it using React.js.

🔧 Tech Stack

- **Frontend:** React.js (Vite + Recharts)
- **Backend:** Node.js + Express
- **Streaming:** Redis Streams (or Kafka)
- **Database:** MongoDB Atlas
- **Deployment:** Vercel (frontend), Render (backend)

📈 Features

- Mock data generation (sensor/finance/etc.)
- Stream ingestion and transformation
- MongoDB time-series storage
- Real-time dashboard with:
  - Live graph
  - Metrics (min, max, avg)
  - Filtering
  - Threshold alerts
