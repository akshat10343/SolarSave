# SolarSave 🌞

SolarSave is a full-stack web app that calculates solar energy potential based on user location.  
It estimates electricity savings, environmental impact, and visualizes solar data!

## Features
- 🌎 Location input (city, zip, etc.)
- ☀️ Real-time solar data from NREL
- 💸 Savings calculator (coming soon!)
- 📈 Environmental impact tracker
- 🔥 Multi-page React + Express fullstack app

Built with:
- React
- Node.js + Express
- Axios
- React Toastify
- OpenCage Geocoder API
- NREL Solar API


## Run it locally

```bash
# 1. API server
cd server
npm install
cp .env.example .env   # add your NREL and OpenCage API keys
node index.js          # runs on http://localhost:5001

# 2. React client (in a second terminal)
cd client
npm install
npm start
```
