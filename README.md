# Keepstreak

**Keep the streak. Build the habit.**

Keepstreak is a daily habit tracker. You mark what you did today, watch your streak grow, and keep track of your personal best. It is simple to use and designed to make consistency visible.

Use it to study, walk, wake up early, or any other habit you want to keep.

> This project is being built as a hands-on practice of backend development with Python. It is developed in stages, and each stage is a piece of the learning, until it becomes a complete product.

## What you can do

- **Create habits:** add the habits you want to track.
- **Mark the day:** record that you completed a habit today.
- **See your streak:** check how many days in a row you have kept and what your best streak was.
- **Browse your history:** see what you did on each day.

## How it works

Data is stored in a PostgreSQL database. An important rule lives in the database itself: the same habit cannot be marked twice on the same day. This keeps the history reliable even when something goes wrong in the code.

The streak rules are kept apart from the user interface, which makes it possible to test the logic carefully, including the tricky cases, such as a day that has not ended yet.

## Stages

- [ ] **1. Database:** tables for habits and check-ins (in progress)
- [ ] **2. Terminal:** create, mark, and list habits from the command line
- [ ] **3. Streaks:** streak and record calculation, with tests
- [ ] **4. API:** the same features over HTTP requests
- [ ] **5. History:** queries and monthly percentages
- [ ] **6. Login and Docker:** each person sees only their own habits, in a standard environment
- [ ] **7. Website:** calendar grid, clean visual, and dark mode
- [ ] **8. Deployment:** the project online, with a public link

## Tech stack

- **Python:** application logic and rules
- **PostgreSQL:** data storage
- **pytest:** automated tests
- **FastAPI:** API (from stage 4)
- **HTML, CSS, and JavaScript:** website (from stage 7)
- **Docker and GitHub Actions:** standard environment and automated tests

## How to run

This section will be filled in once the project has a first usable version.

## License

To be defined.