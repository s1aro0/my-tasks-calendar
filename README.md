# My Tasks Calendar

A clean and minimal calendar-based task planner built with HTML, CSS, and JavaScript.  
The app lets users select a day from the calendar, add tasks, mark them as completed, and track remaining tasks directly from the calendar.

## Features

- Calendar-first task planning
- Add tasks for today and upcoming days
- View past days in read-only mode
- Mark tasks as completed
- Remaining task count displayed on each calendar day
- Internal scrolling for long task lists
- Light and dark mode
- Data saved locally using `localStorage`
- Fully responsive design

## Technologies Used

- HTML5
- CSS3
- JavaScript
- LocalStorage

## How to Run

Open the `index.html` file directly in your browser.

```bash
index.html
```

No installation or backend is required.

## Project Structure

```bash
.
├── index.html
└── README.md
```

## GitHub Pages Deployment

You can publish this project as an interactive website using GitHub Pages.

Steps:

1. Create a new GitHub repository.
2. Upload `index.html` and `README.md`.
3. Go to repository **Settings**.
4. Open **Pages**.
5. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Save the settings.
7. GitHub will generate a live website link for the project.

## Notes

This project stores tasks in the browser using `localStorage`, so the saved tasks are kept on the same browser and device only.
