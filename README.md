Simple Theme Switcher

A minimal React application demonstrating light/dark theme switching using React Context API, Tailwind CSS, and a toggle button. The app also includes a sample product card component styled with Tailwind.

🔗 GitHub Repository: Simple-Theme-Switcher

Features

🌗 Toggle between light and dark mode.

⚛️ Implemented with React Context API for global theme state management.

🎨 Styled with Tailwind CSS for responsive and clean UI.

🛒 Example Card component to demonstrate dark/light styles.

Getting Started
1. Clone the repository
    git clone https://github.com/PinakiRath/Simple-Theme-Switcher.git
    cd Simple-Theme-Switcher

2. Install dependencies
    npm install

3. Run the development server
    npm run dev

4. Build for production
    npm run build

## Project Structure

```plaintext
src
├── App.jsx          # Main app with ThemeProvider
├── App.css          # Global styles
├── components
│   ├── Card.jsx     # Product card UI
│   └── ThemeBtn.jsx # Theme toggle button
└── context
    └── theme.js     # Context + custom hook for theme

Tech Stack
    ->React
    ->Tailwind CSS
    ->Vite