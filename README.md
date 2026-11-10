# AIzen – AI SaaS Application

An AI-powered SaaS application built using the **PERN stack**, featuring user authentication, premium access, and AI-powered content generation tools.

## 🌐 Live Demo

[View AIzen](https://aizen-mu.vercel.app/)

## 🚀 Features

- 🔐 User authentication
- 👤 Role-based premium access
- 🤖 AI-powered image and article generation
- 🖼️ Background and object removal
- 📱 Responsive user interface

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Frontend | React.js, Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | PostgreSQL |
| APIs | AI APIs |

## 📸 Application Preview

### 🔐 Authentication

<img width="50%" alt="AIzen Authentication Page" src="https://github.com/user-attachments/assets/f09e153c-5072-4360-bf51-18c01917f852" />

### 🤖 Home Page

<img width="50%" alt="AIzen Home Page" src="https://github.com/user-attachments/assets/674a36bc-b013-49fc-9076-1f844a580277" />

### 📊 Dashboard

<img width="50%" alt="AIzen Dashboard" src="https://github.com/user-attachments/assets/1633be58-6b1f-4c2e-965f-9438de953579" />

## 📁 Project Structure

```text
AIzen/
├── server/
│   ├── .env.example
│   └── package.json
│
├── client/
│   ├── .env.example
│   └── package.json
│
└── README.md
```
## ⚙️ Getting Started

Follow these steps to run AIzen locally.

### 1. Clone the Repository

```bash
git clone https://github.com/manasiswami/AIzen.git
cd AIzen
```

### 2. Install Backend Dependencies

```bash
cd server
npm install
```

### 3. Configure Backend Environment Variables

Create a `.env` file inside the `server` directory and add the required environment variables.

```env
DATABASE_URL=your_postgresql_connection_url

GEMINI_API_KEY=your_gemini_api_key
CLIPDROP_API_KEY=your_clipdrop_api_key

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret_key

FRONTEND_ORIGIN=http://localhost:5173
```
### 4. Install Frontend Dependencies

Open a new terminal:

```bash
cd client
npm install
```

### 5. Configure Frontend Environment Variables

Create a `.env` file inside the `client` directory if your frontend requires environment variables.

```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_BASE_URL=http://localhost:3000
```
### 6. Run the Application

Start the backend:

```bash
cd server
npm run dev
```

Start the frontend in another terminal:

```bash
cd client
npm run dev
```

Open the local URL displayed by Vite in your browser.

**Note:** Configure your PostgreSQL database and any required database tables or migrations before starting the application.
**Security Note:** Never commit your actual `.env` files or expose secret API keys and credentials in the repository.
