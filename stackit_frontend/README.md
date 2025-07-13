# StackIt - A Minimal Q&A Forum Platform

StackIt is a minimal question-and-answer platform designed for collaborative learning and structured knowledge sharing. It focuses on simplicity, user-friendliness, and the core experience of asking and answering questions within a community.

## Features
- User authentication (login, signup, profile management)
- Ask and answer questions
- Tagging and categorization of questions
- Voting on questions and answers
- Rich text editor for questions and answers
- Responsive and modern UI (built with React, Vite, and TailwindCSS)
- Pagination, search, and filtering for questions
- User profile with stats, badges, and activity

## Getting Started

### Prerequisites
- Node.js (v18 or higher recommended)
- npm or yarn

### Installation
1. Navigate to the `stackit_frontend` directory:
   ```bash
   cd stackit_frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

### Running the Development Server
```bash
npm run dev
# or
yarn dev
```
The app will be available at [http://localhost:5173](http://localhost:5173) by default.

## Project Structure
- `src/` - Main source code
  - `Layouts/` - Page components (Home, Login, SignUp, Profile, AskQuestion, Question)
  - `contexts/` - React context for authentication
  - `assets/` - Static assets
  - `index.css` - TailwindCSS styles
  - `main.jsx` - App entry point
- `public/` - Static files
- `vite.config.js` - Vite configuration
- `eslint.config.js` - ESLint configuration

## Customization
- Update the UI, add backend integration, or extend features as needed for your use case.

## License
This project is for educational and hackathon purposes.

---
Team 0829 | Odoo Hackathon 2025
Team Leader: Krish Kumar Gupta (me.coder.in@gmail.com)
