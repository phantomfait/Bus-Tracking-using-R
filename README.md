# Real-Time Bus Tracking Application

This Shiny application demonstrates real-time bus tracking along routes in New York City. The application shows bus movements on an interactive Google Maps interface with detailed stop information and route visualization.

## Features

- Real-time bus position updates every 2 seconds
- Interactive Google Maps integration
- Detailed bus stop information
- Route visualization with polylines
- Modern UI with rounded edges and smooth animations
- Start/Stop controls for bus simulation

## Prerequisites

- R (>= 4.0.0)
- RStudio (recommended for development)

## Required Packages
install.packages(c("shiny", "googleway", "dplyr", "shinydashboard"))

## Make sure you have enabled the following Google Maps APIs:

   - Maps JavaScript API
   - Places API
   - Geocoding API

## Data Structure

The application uses a CSV file (`bus_routes.csv`) containing the following columns:

- route_id: Unique identifier for the route
- bus_id: Unique identifier for the bus
- stop_name: Name of the bus stop
- latitude: Stop latitude
- longitude: Stop longitude
- sequence: Stop sequence number

