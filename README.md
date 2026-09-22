# PackScore - SE320 Lab 2 Starter Project

## Project
Collaboratively build a Green Bay Packers scoreboard website using GitHub.

## Files
- `index.html` + `css/starter.css`: common starting point
- `data/scoreboard.json`: Scoreboard branch data
- `data/schedule.json`: Schedule branch data
- `data/team-stats.json`: Team Stats branch data

## Branches
- `feature/scoreboard`
- `feature/schedule`
- `feature/team-stats`

The branch examples in `branches/` are instructor reference versions. Students should normally create their own branches from the root starter.

## Important
The three branch versions intentionally replace the same `<main>` section. Students should merge the features rather than choosing one version.

## Running locally
Because the pages use `fetch()` to load JSON files, use a local web server rather than opening `index.html` directly.

Example:
`python3 -m http.server 8000`

Then open:
`http://localhost:8000/`
