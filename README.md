# React Dashboard

A modern, responsive administrative dashboard built with React and Material UI.

## Demo

Live demo: https://jaredmatta.com/ReactDashboard/

---

## Overview

This project is a comprehensive administrative interface designed for data visualization and management. It features a highly customizable sidebar, theme switching (Light/Dark mode), and a variety of complex data views including interactive charts and a full-featured calendar.

---

## Features

- **Data Management:** Interactive tables for Team, Contacts, and Invoices using MUI DataGrid.
- **Visualization:** Advanced Bar, Pie, Line, and Geography charts powered by Nivo.
- **Interactivity:** A functional calendar with event creation and deletion.
- **Form Handling:** A user profile form integrated with Formik and Yup for validation.
- **Theming:** Full Light and Dark mode support with a custom tokenized color palette.

---

## Tech Stack

- **Core:** React 18
- **UI Framework:** Material UI (MUI) & Emotion
- **Routing:** React Router 6
- **Charts:** Nivo
- **Calendar:** FullCalendar
- **Forms:** Formik & Yup

---

## Getting Started

### Prerequisites

- Node.js installed on your machine.
- NPM (comes with Node.js) is required to manage dependencies.

### Installation

1. Clone the repository:
git clone https://github.com/jaredmatta/ReactDashboard.git

2. Navigate into the project:
cd ReactDashboard

3. Run locally (if applicable):
npm install
npm start

Then open:
http://localhost:3000

---

## Usage

### Desktop

- Use the Sidebar to navigate between the Dashboard, Data Management pages, and Visualization charts.
- Toggle the Sidebar width using the menu icon at the top of the sidebar.
- Switch between Light and Dark modes using the icon in the Topbar.

### Mobile

- The sidebar automatically collapses to provide more screen real estate.
- Responsive design ensures charts and data grids scale appropriately.

### Settings / Controls (if applicable)

- **Theme Toggle:** Click the Sun/Moon icon in the top right.
- **Calendar:** Click a date to add an event or click an existing event to delete it.

---

## Key Improvements / Updates

- Implemented a centralized theme management system using React Context.
- Optimized data grid performance for handling mock data sets.
- Integrated advanced SVG-based geography mapping.

---

## Future Improvements

- Fix the routing issue where page refreshes point to alternative subdirectory links.
- Implement real backend API integration to replace mock data.
- Add user authentication and role-based access control (RBAC).

---

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a pull request

---

## Issues

Report bugs or unexpected behavior via the repository’s issue tracker.

---

## License

MIT License

---

## Notes

The project currently uses a `PUBLIC_URL` set to the root for local development. When deploying to a subdirectory like `/ReactDashboard`, ensure the `homepage` field in `package.json` is correctly configured to maintain routing integrity.
