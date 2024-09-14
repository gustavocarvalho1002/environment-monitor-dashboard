# Real-Time Environment Monitor - Data Dashboard
**"Cloud-powered sensor tracking with Raspberry Pi technology."**

This repository contains the **Data Dashboard**, part of the Real-Time Environment Monitor solution. The project is composed of multiple applications that collect, process, and visualize environmental data. This repository handles the visualization layer using a React-based web app.

## Overview
The **Data Dashboard** is a React Web App that displays real-time and historical sensor data captured by the Raspberry Pi and processed by the **Data Ingestion API**. It uses Chart.js for data visualization and SignalR to receive real-time notifications of new data.

## Features
- Visualizes sensor data using various charts.
- Real-time data updates using SignalR.
- Historical data view with filters for specific time ranges.

## Requirements
- Node.js (version X.X)
- React (version X.X)
- Access to the **Data Ingestion API**.

## How to Run
1. Clone this repository.
2. Navigate to the project directory.
3. Install dependencies:
    ```bash
    npm install
    ```
4. Start the development server:
    ```bash
    npm start
    ```

## Configuration
You can configure the API URL for fetching sensor data in the `config.js` file.
