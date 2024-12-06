# FormBuilder

FormBuilder is a web application project designed to provide a seamless experience in creating and managing forms. The project is divided into two main parts: **Frontend** and **Backend**.

---

## Prerequisites

Ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- npm (comes with Node.js)

---

## Getting Started

### 1. Clone the Repository
Clone the repository to your local machine:
```bash
git clone <repository-url>
cd formbuilder
```

### 2. Frontend Setup
Navigate to the `frontend` directory and install the dependencies:
```bash
cd frontend
npm install
```

Start the development server:
```bash
npm run dev
```

The frontend should now be running on `http://localhost:5174` (or the specified port).

---

### 3. Backend Setup
Navigate to the `backend` directory and set up the environment variables:

1. Create a `.env` file by copying the content of `.env.sample`:
   ```bash
   cd backend
   cp .env.sample .env
   ```
2. Open the `.env` file and fill in the necessary values.

Install the dependencies:
```bash
npm install
```

Start the backend server:
```bash
npm run dev
```

The backend should now be running on `http://localhost:8000` (or the specified port).

---

## Project Structure
```
formbuilder/
├── frontend/   # Frontend application (React)
├── backend/    # Backend application (Node.js/Express)
```
