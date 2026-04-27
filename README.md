# ecomm-frontend

A React-based frontend for a full-stack e-commerce application. This project serves as the UI layer for the [sb-ecomm](https://github.com/eholmes83/sb-ecomm) Spring Boot backend.

## Overview

This application displays a browsable product catalog where users can view product details and add items to a shopping cart.

## Tech Stack

- **React 19** + **Vite 8**
- **Tailwind CSS 4**
- **Material UI (MUI) 9**
- **react-hot-toast** — toast notifications
- **react-icons** — icon library

## Features

- Responsive product grid (1–4 columns depending on screen size)
- Product cards showing image, name, description, original price, discount, and sale price
- "Add to Cart" button — disabled automatically when an item is out of stock
- Click on a product image or name to open a detail modal
- Loading and error states with visual feedback

## Components

| Component | Status | Description |
|---|---|---|
| `Products` | ✅ Implemented | Product grid with loading/error states |
| `ProductCard` | ✅ Implemented | Individual product display card |
| `Filter` | 🚧 Stub | Product filtering (not yet implemented) |
| `Pagination` | 🚧 Stub | Pagination controls (not yet implemented) |
| `ProductViewModal` | 🚧 Stub | Product detail modal (not yet implemented) |

## Backend

This frontend is designed to work with the **sb-ecomm** Spring Boot backend:
[https://github.com/eholmes83/sb-ecomm](https://github.com/eholmes83/sb-ecomm)

> **Note:** Product data is currently hardcoded. API integration with the backend is pending.

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```
