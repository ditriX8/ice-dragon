# Ice Dragon

**Live:** https://ice-dragon-dun.vercel.app

Landing page for **Ice Dragon**, a fictional sub-zero drink. It isn't an energy drink: it's a cold drink sold only from branded cryo-fridges at −1°C to −5°C.

## Features

- Dark, handheld-camera look with film grain, flicker, focus hunting and a cursor flashlight
- Dragon eyes that open and close in the dark, follow the cursor and hide from the light
- Three drinks with rotating, draggable 3D cans:
  - Frost Bite, −2°C, $7.99
  - Night Scale, −4°C, $9.99
  - White Fang, −5°C, $14.99
- Top navigation and a detail panel for each drink: price, ingredients, nutrition, how to drink
- Installable as an app (web manifest)

## Run locally

It's a static site: one `index.html`, no build step.

```bash
npx http-server -p 5173 .
```

## Deploy

Deployed on Vercel as a static site. Pushing to `main` redeploys it once the repo is connected to the Vercel project.
