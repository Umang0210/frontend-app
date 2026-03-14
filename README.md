# My Store — Frontend App

A React-based e-commerce storefront built with Vite. Users can browse products, manage a cart, and place orders after authenticating.

## Tech Stack

- **React 19** — UI library
- **React Router DOM 7** — client-side routing
- **Axios** — HTTP client for API communication
- **Vite 7** — development server and build tool
- **ESLint** — code linting

## Features

- Product listing with add-to-cart functionality
- Shopping cart management
- User authentication (login / register / logout)
- Order history for authenticated users

## Project Structure

```
src/
+-- App.jsx              # Root component, routing, global context
+-- main.jsx             # Entry point
+-- assets/              # Static assets
+-- components/
    +-- Header.jsx        # Navigation bar
    +-- Content.jsx       # Product listing page
    +-- Cart.jsx          # Shopping cart page
    +-- Orders.jsx        # Order history page
    +-- Login.jsx         # Login form
    +-- Register.jsx      # Registration form
    +-- Logout.jsx        # Logout handler
```

## Getting Started

### Prerequisites

- Node.js 18 or later
- npm 9 or later

### Installation

```bash
npm install
```

### Environment Variables

Create a `.env` file in the project root:

```env
VITE_API_URL=http://localhost:5000
```

| Variable        | Description                     |
| --------------- | ------------------------------- |
| `VITE_API_URL`  | Base URL of the backend API     |

### Running the Development Server

```bash
npm run dev
```

The app will be available at `http://localhost:5173`.

### Building for Production

```bash
npm run build
```

The production-ready files are output to the `dist/` directory.

### Previewing the Production Build

```bash
npm run preview
```

### Linting

```bash
npm run lint
```

## Deployment

After running `npm run build`, deploy the contents of the `dist/` folder to any static hosting provider (e.g., Vercel, Netlify, GitHub Pages, AWS S3).

## License

This project is private.
