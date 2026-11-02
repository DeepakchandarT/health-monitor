# Pulseboard

Pulseboard is a responsive, read-only Firebase Realtime Database dashboard for synthetic wearable vitals.

## Features

- Live heart rate, SpO2, temperature, ECG, humidity, battery, connectivity, wear, charging, and sensor status
- Responsive canvas charts with 60-point history
- Correct handling for disabled, unavailable, unworn, and stale values
- Snapshot JSON export
- No Firebase SDK, API key, password, or write operation

## Data source

The dashboard reads from:

`https://vitals-tracker-d0f7b-default-rtdb.firebaseio.com/`

It supports values under `/Health` and `/Simulator`, including the synthetic metadata written by the companion demo sender.

## Local use

Open `index.html` in a browser or serve this folder with any static file server.

## Deployment

The project is configured as a static Vercel site.

