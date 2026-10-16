# Jeju 2026

Our five-day Jeju road trip, Saturday 17 to Wednesday 21 October 2026, as a single web page. It has the day-by-day plan with Naver Map drive times, Naver, Kakao and Google Maps links for every stop, three to five food and coffee picks per meal, rain plans and photos.

## Opening it

- **As a website:** go to Settings → Pages, choose "Deploy from a branch", then `main` and `/ (root)`. GitHub Pages for a private repo needs a paid GitHub plan, and anyone with the site's link can open it. The page asks search engines not to list it.
- **On your computer:** download the repo, run `python3 -m http.server` in this folder and open http://localhost:8000. Opening `index.html` straight from disk won't load the plan, because browsers block a local file from reading `trip.json`.

## What's in here

- `index.html` is the whole app.
- `trip.json` is the plan: days, stops, food picks, rain plans, hotels, flights and the car.
- `routes.json` holds the Naver Map drive times and road shapes.
- `img/` holds the photos, all from Wikimedia Commons. Their credits are listed at the bottom of the page.

On this copy, ticks, picks and notes are saved in the browser you make them in.
