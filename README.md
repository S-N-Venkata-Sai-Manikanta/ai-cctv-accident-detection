# AI CCTV Accident Detection System

## Features
- Vehicle Counting
- Accident Detection
- Manual Alerts
- Real-time Dashboard

## Run Frontend
npm install
npm run dev

## Run Backend
node server.js

## Run AI Service
python app.py

## Deploy on Render
1. Push this project to GitHub.
2. In Render, choose New + and select Blueprint.
3. Connect the repository and deploy using render.yaml.
4. Render will create three services:
	- accident-frontend
	- accident-backend
	- accident-ai-service

### Notes
- Backend and AI service now read PORT from environment automatically.
- Frontend is deployed as a static site from frontend/dist.
