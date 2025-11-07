🔍 Search GitHub User App

A modern web application that allows users to search GitHub profiles and view detailed user information — including repositories, followers, and other public data — using the GitHub GraphQL API.
Built with React, Vite, Apollo Client, and styled using Tailwind CSS and Radix UI for an elegant, responsive experience.

🚀 Features

🔎 Search any GitHub user by username

👤 View profile details (avatar, bio, followers, following, etc.)

📦 List public repositories with descriptions and stars

📈 Interactive charts using Recharts

⚡ Fast and responsive UI powered by Vite + Tailwind CSS

🎨 Smooth animations via @formkit/auto-animate and tailwindcss-animate

🧠 GraphQL data fetching using Apollo Client

🧩 Reusable UI components with Radix UI and Lucide icons

🛠️ Tech Stack
Category Technologies
Frontend React 18, TypeScript, Vite
UI & Styling Tailwind CSS, Radix UI, Tailwind Animate, clsx
State & Data Apollo Client, GraphQL
Icons Lucide React, React Icons
Charts Recharts
Animations Auto Animate
Testing Vitest, Testing Library
Linting ESLint, TypeScript ESLint
⚙️ Installation & Setup

Clone this repository

git clone https://github.com/yourusername/search-github-user-app.git
cd search-github-user-app

Install dependencies

npm install

Create an .env file

VITE_GITHUB_TOKEN=your_personal_access_token

🪪 You need a GitHub personal access token
to use the GraphQL API.
The token must have read-only public_repo permissions.

Run the app

npm run dev

Build for production

npm run build

Preview the production build

npm run preview

🧪 Testing

To run the tests:

npm run test

📁 Project Structure
search-github-user-app/
├── src/
│ ├── components/ # Reusable UI components
│ ├── pages/ # App pages (Home, UserProfile, etc.)
│ ├── graphql/ # Queries and mutations
│ ├── hooks/ # Custom React hooks
│ ├── utils/ # Helpers and constants
│ ├── App.tsx # Root component
│ └── main.tsx # Entry point
├── public/ # Static assets
├── package.json
├── tailwind.config.js
├── tsconfig.json
└── vite.config.ts

🧾 Scripts
Command Description
npm run dev Start local development server
npm run build Build for production
npm run preview Preview production build
npm run test Run all unit tests
npm run lint Run ESLint for code quality
📜 License

This project is licensed under the MIT License.
See the LICENSE
file for details.

💡 Acknowledgements

GitHub GraphQL API

Apollo Client

Vite

Tailwind CSS

Radix UI

Recharts
