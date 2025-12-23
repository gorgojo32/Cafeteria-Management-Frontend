# Frontend - Sistema de Gestión de Cafetería (React)

This project is a web application built with React that allows administrators to manage products and categories for a coffee shop system. This repository contains the frontend part of the application.

## Features

- `Manage Products:` Create, edit, and delete products with image upload functionality.
- `Manage Categories:` Full CRUD operations for product categories.
- `Interactive Dashboard:` Modern administrative interface with Material-UI components.
- `Image Preview:` View and manage product images before uploading.
- `Responsive Design:` Works seamlessly on mobile, tablet, and desktop devices.

## Installation

When you download this project, drag the folder to Visual Studio Code then open the terminal and execute this command

First command in the terminal
```bash
# Navigate to the project folder
cd vite

# Install dependencies
npm install
```



## PAGE FUNCTIONALITY

<div align="center">
  <table>
    <tr>
      <td style="padding: 10px; background: white;">
        <img src="https://github.com/user-attachments/assets/e85b8e1a-373c-4141-95a8-292964678541" width="550">
      </td>
      <td style="padding: 10px; background: white;">
        <img src="https://github.com/user-attachments/assets/60abc4ad-fdea-48ac-b6b2-3743f0a8ecaa" width="550">
      </td>
    </tr>
    <tr>
      <td style="padding: 10px; background: white;">
        <img src="https://github.com/user-attachments/assets/39723b3f-59e2-4080-bbbd-86b3d87d81fd" width="550">
      </td>
      <td style="padding: 10px; background: white;">
        <img src="https://github.com/user-attachments/assets/2a20bb28-6e52-4d9e-87d0-7b787f74a0dc" width="550">
      </td>
    </tr>
    <td style="padding: 10px; background: white; text-align: center;">
        <img src="https://github.com/user-attachments/assets/2a20bb28-6e52-4d9e-87d0-7b787f74a0dc" width="550">
      </td>
  </table>
</div>




## Required Extensions for Visual Studio Code

Before running the project, make sure you install the following extensions in VS Code:

### ES7+ React/Redux/React-Native snippets - REQUIRED

- Provides comprehensive snippets for React, Redux, and React-Native
- Supports ES7+ syntax with customizable options
- Built-in integration with prettier for consistent formatting

## Usage

### Main Dashboard
The main interface where you can access all management features including products, categories, and information sections.

### Product Management
- View all products in a table format with images
- Add new products with details like name, description, price, cost, stock, and image
- Edit existing products with real-time validation
- Delete products with confirmation dialog

### Category Management
- List all product categories
- Create new categories with type and description
- Edit category information and status
- Delete categories when needed

### Information Section
Interactive menu with:
- **Coffee Products:** Display featured coffee products with cards
- **Store Locations:** Show store information with addresses and features

## Technologies

- `React with TypeScript:` For building the interactive user interface with strong typing
- `Material-UI (MUI):` Professional UI components and design system
- `React Router:` For navigation between different sections
- `Vite:` Fast build tool and development server

## Project Structure

```
vite/
├── node_modules/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── .gitkeep
│   ├── layouts/
│   │   └── dashboard.tsx          # Main dashboard layout with gradient background
│   ├── pages/
│   │   ├── index.tsx               # Main page with product and category management
│   │   ├── App.tsx                 # Application routing and structure
│   │   └── main.tsx                # Entry point that starts the app
│   └── components/
│       ├── MenuButton.tsx          # Custom menu button with animations
│       ├── MenuCafe.tsx            # Coffee products display component
│       ├── MenuNovedades.tsx       # Store locations display component
│       ├── Menus.tsx               # Interactive menu container
│       ├── mAgregarCtga.tsx        # Modal for adding new category
│       ├── mEditarCtga.tsx         # Modal for editing category
│       ├── mAgregarProd.tsx        # Modal for adding new product
│       └── ModalProducto.tsx       # Modal for editing product
├── .gitignore
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

## Available Scripts

First command in the terminal
```bash
# Navigate to project directory
cd vite
```

Second command in the terminal
```bash
# Run in development mode
npm run dev
```

Third command (optional)
```bash
# Build for production
npm run build
```

## Configuration

Make sure the backend API is running on `http://localhost:8000` before starting the frontend application.

If you need to change the API URL, update the fetch calls in the components to point to your backend server.
