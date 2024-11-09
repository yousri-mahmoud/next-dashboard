# Next.js Dashboard

A modern, feature-rich dashboard application built with Next.js, React, and Tailwind CSS.

## Features

- Responsive design optimized for desktop and mobile devices
- Real-time data visualization with interactive charts and graphs
- User authentication and role-based access control
- CRUD operations for efficient data management
- Dark mode for comfortable viewing in low-light environments
- Server-side rendering for improved performance and SEO
- API routes for secure backend functionality

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (version 14.0 or later)
- npm, yarn, or pnpm package manager
- Git

## Getting Started

Follow these steps to get the dashboard up and running on your local machine:

1. Clone the repository:

   ```
   git clone https://github.com/your-username/nextjs-dashboard.git
   ```

2. Navigate to the project directory:

   ```
   cd nextjs-dashboard
   ```

3. Install the dependencies:

   Using npm:

   ```
   npm install
   ```

   Using yarn:

   ```
   yarn install
   ```

   Using pnpm:

   ```
   pnpm install
   ```

4. Set up environment variables:

   Copy the `.env.example` file to `.env.local` and fill in the required values:

   ```
   cp .env.example .env.local
   ```

   Open `.env.local` and update the variables with your specific configuration.

5. Run the development server:

   Using npm:

   ```
   npm run dev
   ```

   Using yarn:

   ```
   yarn dev
   ```

   Using pnpm:

   ```
   pnpm dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser to see the dashboard.

7. Log in using the following credentials:
   - Email: user@nextmail.com
   - Password: 123456

## Project Structure

- `/pages`: Contains all the pages of the application
- `/components`: Reusable React components
- `/styles`: Global styles and Tailwind CSS configuration
- `/lib`: Utility functions and custom hooks
- `/public`: Static assets like images and fonts

## Available Scripts

In the project directory, you can run:

- `npm run dev` or `yarn dev` or `pnpm dev`: Runs the app in development mode
- `npm run build` or `yarn build` or `pnpm build`: Builds the app for production
- `npm start` or `yarn start` or `pnpm start`: Runs the built app in production mode
- `npm run lint` or `yarn lint` or `pnpm lint`: Lints the codebase using ESLint

## Acknowledgments

- [Next.js](https://nextjs.org/) - The React Framework for Production
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework
- [React Query](https://react-query.tanstack.com/) - Hooks for fetching, caching and updating asynchronous data
- [Chart.js](https://www.chartjs.org/) - Simple yet flexible JavaScript charting
- [NextAuth.js](https://next-auth.js.org/) - Authentication for Next.js
