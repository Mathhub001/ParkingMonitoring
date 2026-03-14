# AI-Based Automated Parking Slot Monitoring System

## Project Overview
This project is an AI-driven automated parking slot monitoring system designed for urban environments. It uses YOLOv8 for real-time vehicle detection and Streamlit for an interactive dashboard. The system monitors parking slot occupancy in real time, provides notifications for newly occupied slots, and captures snapshots for record-keeping.

## Features
- Real-Time Vehicle Detection (car, truck, bus, motorbike, bicycle)
- Interactive Dashboard with slot status (green = free, red = occupied)
- Start / Stop / Reset controls at top-right
- Vehicle notifications for newly occupied slots
- Automatic snapshots saved in `snapshots/` folder
- Dashboard metrics: total, available, occupied slots
- Optimized layout: camera left, controls + metrics right

## How to Run
1. Upload this folder to Streamlit Cloud.
2. Ensure `requirements.txt` is present in the root.
3. Deploy the app; Streamlit Cloud installs dependencies automatically.
4. Open the app dashboard at the provided URL.

## Usage
- **Start Monitoring**: Activates the camera for live detection.
- **Stop Monitoring**: Stops the camera feed.
- **Reset Parking System**: Resets all slots to free.
- **Snapshots**: Captured automatically when a slot becomes occupied.