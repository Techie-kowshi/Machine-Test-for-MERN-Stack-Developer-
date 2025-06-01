
# MERN Stack Machine Test Application

This is a full-stack MERN (MongoDB, Express.js, React, Node.js) test application scaffolded using Vite and Tailwind CSS. It is intended as a machine test project or template.

## 📁 Project Structure

- `src/` – Contains application source code
- `vite.config.ts` – Vite configuration file
- `tailwind.config.js` – Tailwind CSS configuration
- `setup.mjs` – Setup or initialization script
- `.env.local` – Environment-specific variables (excluded from version control)

## ✅ Prerequisites

Make sure you have the following installed:

- [Node.js (v18+ recommended)](https://nodejs.org)
- npm (comes with Node.js)
- MongoDB (if backend connects to a DB)

## 🚀 Setup Instructions

1. **Clone the repository / Extract ZIP**  
   Unzip or clone the repository to your local machine.

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up environment variables**  
   Create a `.env.local` file in the root directory and add your environment variables as needed. You can refer to the existing `.env.local` example.

4. **Run the development server**

   ```bash
   npm run dev
   ```

   The application will start on `http://localhost:5173` (or another port if configured).

## ⚙️ Scripts

- `npm run dev` – Start the development server
- `npm run build` – Create a production build
- `npm run preview` – Preview the production build locally

## 📦 Build for Production

To build the application for production:

```bash
npm run build
```

The output will be in the `dist/` directory.

## 📝 Notes

- Tailwind CSS is used for styling.
- TypeScript is enabled.
- Make sure MongoDB or any required backend is running if the frontend depends on it.
