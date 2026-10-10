# DelightHub — Base44 Dev Environment

## Project
Single-page static HTML site (`index.html`). No build step, no backend, no dependencies, no external services.

## Running
```
docker compose -f docker-compose.base44.yml up -d
```
Serves `index.html` via nginx:alpine on host port 3000.

## Verification
- `curl -s http://localhost:3000/ | grep -q DelightHub` confirms the page loads.
- The preview should show the landing page with hero, projects, tutorials, tools, and community sections.

## No secrets required
This project has no external service dependencies.
