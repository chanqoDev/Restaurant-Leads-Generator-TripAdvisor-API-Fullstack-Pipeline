# Restaurant Leads Generator (TripAdvisor API + Fullstack Pipeline)

---

## Overview
A fullstack application that generates restaurant leads using the TripAdvisor API. The system processes user input, retrieves external data, and stores structured results in a database for further use.

---

## Features
- Fetch restaurant data using TripAdvisor API  
- Generate leads based on user input (e.g., zipcode/location)  
- Store and manage leads in MySQL database  
- Display results in a dynamic React UI  
- Backend API for handling data processing and storage  

---

## Tech Stack
- Frontend: React, Material UI  
- Backend: Node.js, Express  
- Database: MySQL  
- APIs: TripAdvisor API  

---

## Architecture
- React frontend sends requests to backend API  
- Express server processes input and calls external API  
- Data is normalized and stored in MySQL  
- Results are returned and rendered dynamically in the UI  

---

## How It Works
- User inputs a location or zipcode  
- Backend queries TripAdvisor API for restaurant data  
- API returns structured data including ratings, location, and details :contentReference[oaicite:0]{index=0}  
- Data is processed and stored in MySQL  
- Frontend displays generated leads in real time  

---

## Getting Started

Install dependencies:
```bash
npm install
npm run server
npm start
```

### Highlights
Integrated third-party API for real-world data retrieval
Built backend pipeline for data transformation and storage
Designed fullstack flow from user input to database persistence
Demonstrates practical use case (lead generation system)

### Future Improvements
Add filtering and sorting (rating, location, price)
Implement pagination and rate limiting
Improve error handling and API resilience
Deploy with cloud database and hosting
