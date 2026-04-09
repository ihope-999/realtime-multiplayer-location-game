# Location Guessing Game

A real-time multiplayer web game where players compete to guess 
locations on Google Maps. Built with C# and ASP.NET Core, featuring 
live interactions powered by SignalR.

## Features

- **Real-time multiplayer** — players interact live using SignalR WebSockets
- **Google Maps integration** — locations fetched and displayed via Google Maps API
- **Role-based system** — Admin and User roles with different permissions
- **Secure authentication** — login system with role management
- **Containerized** — runs fully in Docker with a single command

## Tech Stack

- **Backend:** C# / ASP.NET Core
- **Real-time:** SignalR
- **Database:** PostgreSQL (containerized)
- **API:** Google Maps API
- **Infrastructure:** Docker 
- **Frontend:** HTML, CSS


Navigate to **http://127.0.0.1:5000** in your browser.

### Demo accounts

| Username | Password | Role |
|----------|----------|------|
| admin | admin | Admin |
| john | john | Player |
| ola | ola | Player |

## Architecture

- ASP.NET Core backend handles game logic and user management
- SignalR hub manages real-time communication between players
- PostgreSQL stores users, roles, and game data
- Google Maps API provides location data for each round
- Docker Compose orchestrates all services together

- more will be added
