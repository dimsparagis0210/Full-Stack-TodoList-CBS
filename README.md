# 📝 Todo Cosmos

A full-stack todo application built with React (Frontend) and Spring Boot (Backend), containerized with Docker Compose.

## 🏗️ Architecture

- **Frontend**: React + TypeScript + Vite
- **Backend**: Spring Boot + Java 21 + PostgreSQL
- **Database**: PostgreSQL 15
- **Containerization**: Docker & Docker Compose

## 🚀 Quick Start with Docker Compose

### Prerequisites

Make sure you have the following installed:
- [Docker](https://docs.docker.com/get-docker/) (version 20.10+)
- [Docker Compose](https://docs.docker.com/compose/install/) (version 2.0+)

### 🐳 Running the Application

1. **Clone the repository** (if not already done):
   ```bash
   git clone https://github.com/dimsparagis0210/Full-Stack-TodoList-CBS.git
   cd todo-cosmos
   ```

2. **Start all services**:
   ```bash
   docker compose up
   ```
   
   Or run in detached mode (background):
   ```bash
   docker compose up -d
   ```

3. **Access the application**:
   - **Frontend**: http://localhost:5173
   - **Backend API**: http://localhost:8080
   - **Database**: localhost:5432

