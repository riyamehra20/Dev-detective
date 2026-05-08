#  Dev Detective — GitHub User Search App

A sleek, detective-themed GitHub user search app built with **HTML, CSS, and Vanilla JavaScript**. Search any GitHub username and instantly pull their public profile data using the GitHub REST API.

## Live Demo

 **[View Live Site](https:/dev-detective-riya.netlify.app)**

##  Features

-  Search any GitHub user by username
-  Displays avatar, name, bio, join date, location, portfolio & organisation
-  Shows public repos, followers, and following count
-  Loading state while data is being fetched
-  Friendly error message for invalid usernames (404)
-  Network error handling — app never crashes
-  Fully responsive on mobile and desktop


##  Built With

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure |
| CSS3 | Styling & animations |
| Vanilla JavaScript | Logic & API calls |
| Fetch API | HTTP requests |
| Async / Await | Asynchronous handling |
| GitHub REST API | Live user data |


##  API Used
- **Free & public** — no API key required
- Rate limit: **60 requests/hour** per IP (unauthenticated)
- Docs: [developer.github.com](https://docs.github.com/en/rest/users/users)

---

## Project Structure
dev-detective/
│
├── index.html       ← Main app (HTML + CSS + JS in one file)
├── README.md        ← You are here
└── prompt.md        ← Developer prompts used to build this app