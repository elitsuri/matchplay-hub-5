# MatchPlay Hub

> Multiplayer matchmaking with ranking, lobby, and stats tracking

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
C++, SFML, SQLite, CMake

## 🏗️ Architecture
Backend service with C++, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/matchplay-hub
cd matchplay-hub

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
