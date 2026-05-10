# Student Management Portal — Angular Frontend

The **Angular frontend** for the Student Management Portal — a single-page application for viewing, adding, editing, and deleting student records.

## What it does

Provides a clean UI for managing students. Connects to the [Student Management Portal API](https://github.com/AhmedElneziliiy/Student-Management-Portal-API) to fetch and update student data in real time.

## Tech Stack

- **Angular** — component-based SPA
- **TypeScript**
- **Angular Services** — HTTP client for API integration
- **Angular Router** — client-side navigation

## Key Features

- Student list view with inline actions
- Add and edit student form with address fields
- Gender selection
- Angular service layer for clean API communication
- Separate API and UI models (domain separation)
- Top navigation component

## Project Structure

```
src/app/
├── layout/top-nav/       # Navigation bar component
├── models/
│   ├── api-models/       # Raw API response shapes
│   └── ui-models/        # UI-friendly model types
├── services/             # HTTP services (students, genders)
└── students/             # Student list and form components
```

## Getting Started

1. Make sure the [API](https://github.com/AhmedElneziliiy/Student-Management-Portal-API) is running.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the dev server:
   ```bash
   ng serve
   ```
4. Open `http://localhost:4200`.
