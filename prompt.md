##  API & Fetch

- What is the correct GitHub REST API endpoint to fetch a user's profile?
- How do I use `fetch()` to make a GET request to an external API?
- What does `async/await` do and why should I use it instead of `.then()`?
- What fields does the GitHub API return? (e.g. `avatar_url`, `bio`, `created_at`)
- How do I format the `created_at` ISO date string into a readable format?


##  Error Handling

- What HTTP status code does GitHub return when a user is not found?
- How do I check `response.ok` and `response.status` after a fetch call?
- How do I show a user-friendly message instead of crashing the app on a 404?
- What happens if the user has no internet? How do I catch a network failure?
- Should I wrap my fetch call in a `try/catch` block — and why?
- How do I prevent the app from showing stale data if a new search is made?

##   Loading & UI States

- What are the different UI states my app needs? (empty, loading, success, error)
- How do I show and hide different sections of the page using JavaScript?
- How do I create a CSS spinner animation for the loading state?
- Should I disable the search button while a request is in progress?

##   JavaScript Logic

- How do I listen for both a button click AND the Enter key on an input field?
- How do I safely encode a username before putting it in a URL?
- How do I conditionally show or hide a field if the API returns `null`?
- How do I format large numbers like `12000` into `12k` for display?
- How do I auto-prefix `https://` to a blog URL that might be missing it?


## 8.  Testing & Polish

- How do I test the 404 error state? 
- How do I test the network error state? 