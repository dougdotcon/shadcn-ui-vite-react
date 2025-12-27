# ShadcnViteReactTemplate

A streamlined template for rapidly building modern web applications using **shadcn/ui** component library with **Vite** and **React**. It provides a pre-configured JavaScript environment, ensuring a smooth and efficient development workflow.

## 🚀 Features

- **Modern Stack**: Built with Vite, React, and Tailwind CSS.
- **Component Library**: Pre-installed and configured [shadcn/ui](https://ui.shadcn.com/).
- **Fast HMR**: Lightning-fast development server with Vite.
- **Clean Structure**: Minimal boilerplate to get you started immediately.
- **ESLint & Prettier**: Basic configuration for code consistency.

## 📦 Prerequisites

- Node.js (v18+ recommended)
- npm or yarn (we use npm in these examples)

## ⚡ Quick Start

1. **Clone the repository**
   bash
   git clone https://github.com/your-username/shadcn-ui-vite-react.git
   cd shadcn-ui-vite-react
   

2. **Install dependencies**
   bash
   npm install
   

3. **Run the development server**
   bash
   npm run dev
   

4. **Open your browser**
   Visit `http://localhost:5173` to see your application.

## 📂 Project Structure

bash
├── public/
├── src/
│   ├── components/
│   │   └── ui/          # shadcn/ui components
│   ├── App.jsx
│   └── main.jsx
├── .eslintrc.cjs
├── .prettierrc
├── tailwind.config.js
├── components.json       # shadcn/ui configuration
└── vite.config.js


## 🛠️ Available Scripts

- `npm run dev`: Starts the development server.
- `npm run build`: Compiles the application for production.
- `npm run preview`: Locally previews the production build.
- `npm run lint`: Checks for linting errors.

## 🧩 Adding Components

This template uses `shadcn/ui`. To add new components, run the `init` command (if not already done) and then add specific components:

bash
# Initialize (usually already done in this template)
npx shadcn-ui@latest init

# Add a button component
npx shadcn-ui@latest add button


Refer to the [shadcn/ui documentation](https://ui.shadcn.com/docs/installation) for more details.

## 📄 License

MIT License. Feel free to use this template for your projects.