# Society Maintenance Tracker

A comprehensive full-stack web application designed to streamline and manage society maintenance tracking. This platform empowers residents and administrators to efficiently handle maintenance requests, payments, and communications in one centralized hub.

## 🚀 Tech Stack

### Frontend
- **Framework**: [React 19](https://react.dev/) powered by [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **State Management**: [TanStack React Query](https://tanstack.com/query/latest)
- **Routing**: [React Router](https://reactrouter.com/)
- **Language**: TypeScript

### Backend
- **Server**: [Node.js](https://nodejs.org/) & [Express](https://expressjs.com/)
- **Database ORM**: [Prisma](https://www.prisma.io/)
- **Authentication**: JWT (JSON Web Tokens) & bcrypt
- **Language**: TypeScript

## 📁 Project Structure

The repository is organized into a monorepo-style structure:

- `/frontend` - Contains the React Vite application
- `/backend` - Contains the Express server and database models

## 🛠️ Getting Started

### Prerequisites

Ensure you have the following installed:
- Node.js (v18 or higher recommended)
- A preferred package manager (npm, yarn, or pnpm)
- Access to your database (e.g., PostgreSQL or MySQL based on your Prisma configuration)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RaunakSachdeva2004/society-maintenance-tracker.git
   cd society-maintenance-tracker
   ```

2. **Setup the Backend:**
   ```bash
   cd backend
   npm install
   # Setup your environment variables (.env) based on the database and JWT secrets needed
   # Run Prisma migrations
   npx prisma migrate dev
   npm run dev
   ```

3. **Setup the Frontend:**
   ```bash
   cd ../frontend
   npm install
   npm run dev
   ```

## 🔒 Features (In Progress)
- User Authentication (Login, Register)
- Maintenance Request submission and tracking
- Admin dashboard for overseeing society operations

## 📄 License
This project is licensed under the ISC License.
