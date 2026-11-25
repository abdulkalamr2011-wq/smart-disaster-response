# Smart Disaster Response

A browser-based demonstration of the disaster response capstone described in the project review deck. The page presents an illustrative dispatch dashboard for incident prioritization, response resources, route status, and activity logging.

## Demo controls

- **Report incident** adds a simulated incident to the priority queue.
- **Run simulation** generates a sample incident.
- The dashboard map, metrics, and chart use illustrative training data only.

This is a frontend project demo. It does not connect to emergency services, live maps, or dispatch systems.

## Run locally

Open `index.html` in a modern browser. No build step or dependencies are required.

## Publish

GitHub Actions publishes the static page to GitHub Pages after changes are pushed to `main`. See `.github/workflows/deploy.yml`.
