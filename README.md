# 📝 Notes App

A modern, responsive notes application built with React. Create, edit, search, and manage your notes with an intuitive and beautiful user interface.

![React](https://img.shields.io/badge/React-18.2.0-blue.svg)
![Vite](https://img.shields.io/badge/Vite-4.4.5-646CFF.svg)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.3.3-38B2AC.svg)

## ✨ Features

- **Create Notes**: Easily create new notes with titles and detailed content
- **Edit Notes**: Update existing notes with real-time editing
- **Delete Notes**: Remove unwanted notes with a confirmation prompt
- **Search Functionality**: Quickly find notes by searching through titles
- **Local Storage**: All notes are automatically saved to browser local storage
- **Responsive Design**: Fully responsive and works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Beautiful gradient design with a dark theme

## 🛠️ Tech Stack

- **React** - UI library
- **React Router DOM** - Client-side routing
- **Vite** - Build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **React Icons** - Icon library
- **UUID** - Unique ID generation for notes

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd notes_app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## 🚀 Usage

### Development Mode

Run the development server:

```bash
npm run dev
```

The app will be available at `http://localhost:5173` (or the port shown in the terminal).

### Build for Production

Create an optimized production build:

```bash
npm run build
```

### Preview Production Build

Preview the production build locally:

```bash
npm run preview
```

### Linting

Run ESLint to check for code issues:

```bash
npm run lint
```

## 📁 Project Structure

```
notes_app/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   ├── NoteItem.jsx      # Individual note card component
│   │   └── useCreateDate.jsx  # Custom hook for date formatting
│   ├── pages/
│   │   ├── Notes.jsx          # Main notes listing page
│   │   ├── CreateNote.jsx     # Create new note page
│   │   └── EditNote.jsx       # Edit existing note page
│   ├── App.jsx                # Main app component with routing
│   ├── main.jsx               # Application entry point
│   └── index.css              # Global styles
├── index.html
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
```

## 🎯 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🔑 Key Features Explained

### Notes Management
- All notes are stored in the browser's local storage
- Each note has a unique ID generated using UUID
- Notes include title, details/content, and creation/edit date

### Search
- Click the search icon to activate search mode
- Search filters notes by title (case-insensitive)
- Search updates in real-time as you type

### Navigation
- Home page (`/`) - View all notes
- Create page (`/create-note`) - Add new notes
- Edit page (`/edit-note/:id`) - Modify or delete existing notes

## 🎨 Design

The app features a modern dark theme with:
- Gradient buttons and accents
- Smooth transitions
- Responsive grid layout for notes
- Clean and minimal interface

## 📝 License

This project is private and not licensed for public use.

## 👤 Author

Built as a React learning project.

---

Happy note-taking! 📝

