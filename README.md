# Student Management Portal — Angular Frontend

The **Angular frontend** for the Student Management Portal — a single-page application for viewing, adding, editing, and deleting student records.

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
2. Install dependencies: `npm install`
3. Start the dev server: `ng serve`
4. Open `http://localhost:4200`.
