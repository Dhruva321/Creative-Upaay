# Creative Upaay Dashboard - Pixel-matched scaffold

This is a React + Tailwind + Redux Toolkit scaffold implementing the Creative Upaay dashboard UI.
The implementation matches the Figma tokens you provided for the board area (typography, colors, card styles) and includes a Sidebar component.

## What is included
- React app skeleton (src/)
- Redux Toolkit slices for tasks and projects
- Components: Sidebar, Column, TaskCard, AddTaskModal
- Drag & drop using react-beautiful-dnd (used for board tasks)
- Tailwind setup (basic)

## How to run locally
1. `npm install`
2. `npm start`
3. Open http://localhost:3000

## Notes
- The project uses Inter font; add the Google Fonts link in `public/index.html` or include in CSS.
- Styling is Tailwind-based and uses inline colors to exactly match Figma tokens provided.
- State persists to localStorage.

