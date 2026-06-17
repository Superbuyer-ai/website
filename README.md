# Superbuyer — Company Website

The official website for **New Superbuyer Inc.** (brand: *Superbuyer*) — an AI robotics
company building autonomous food & grocery delivery.

🌐 Live: https://superbuyerai.com

## Stack
Static site — plain HTML / CSS / vanilla JS. No build step.

## Structure
```
index.html      Home
contact.html    Contact page (Netlify Forms)
thanks.html     Post-submit confirmation
styles.css      Shared stylesheet
images/         Image assets (hero robot, etc.)
```

## Local preview
```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## Deploy
Hosted on Netlify. Pushing to `main` triggers an automatic deploy.
