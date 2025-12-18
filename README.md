Equipment Tracker

## Overview

A simple web app to manage equipment. Users can add, edit, delete, and view equipment items.

## Features

* Add new equipment
* Edit existing equipment
* Delete equipment
* View all equipment in a table
* Each item has:

  * Name
  * Type (Machine, Vessel, Tank, Mixer)
  * Status (Active, Inactive, Under Maintenance)
  * Last Cleaned Date

## Technologies

* Frontend: React.
* Backend: Node.js, Express
* Database: JSON file (equipment.json)

## How to Run Locally

### Backend

1. Open terminal in backend folder
2. Run: npm install
3. Run: node server.js
4. Backend runs on: http://localhost:5000

### Frontend

1. Open terminal in frontend folder
2. Run: npm install
3. Run: npm start
4. Open browser at http://localhost:3000 (or next available port)

## Assumptions

* Using local JSON file, no database
* No authentication required

## Possible Improvements

* Use a real database like MongoDB or PostgreSQL
* Add search, filter, and sorting
* Mobile-responsive design
* Better backend error handling
