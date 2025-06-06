# React + Vite Setup

This project uses **React** with **Vite** for fast development and hot module replacement (HMR). Below are the steps to get started.

## 🚀 Getting Started

### 1. Install Dependencies

```bash
npm install
npm install lucide-react
```

### 2. Run the Development Server

```bash
npm run dev
```

This will start the Vite development server and open the app in your browser.

## 🔐 Environment Variables

To use external APIs, create a `.env` file in the root of the project:

```
VITE_API_URL=https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=YOUR-API-KEY-HERE
```

> Replace `YOUR-API-KEY-HERE` with your actual API key.

## 📦 Dependencies Used

- `react`
- `react-dom`
- `vite`
- `lucide-react`
