# Bear Labs — Portfolio

Static portfolio site for “Bear Labs” showcasing apps/projects and a contact page.

## Pages

- **Home**: [index.html](index.html)
  - Hero section with avatar, short intro, and CTA buttons
  - Projects section with 10 project cards
- **Contact**: [contact.html](contact.html)
  - Contact form that opens the user’s email app using a pre-filled `mailto:` link

## Tech Stack

- HTML (no framework)
- CSS (custom styles in [styles.css](styles.css))
- Vanilla JavaScript (smooth scrolling + minor UI behavior in [script.js](script.js))

## Features

- Responsive layout (2-column project grid on desktop, 1-column on smaller screens)
- Sticky header navigation
- Smooth scrolling for in-page anchors (`#projects`)
- Dark theme UI with CSS variables
- Contact form that pre-fills an email to `atharvamahabal8@gmail.com`

## Projects (Cards on Home Page)

The Home page lists the following projects:

1. FirstLight
2. dungeon-game
3. WeightTracker
4. ThingworxAgent
5. DailyTasks
6. QuietSpace
7. Market-Research
8. Learning-App
9. home-automation

## Run Locally

Because this is a static site, you can run it in a few simple ways:

### Option A: Open directly

- Open `index.html` in a browser.

### Option B: Use a local server (recommended)

This avoids any browser restrictions around local file access and keeps navigation consistent.

- **Python**
  - From the project folder:
    - `python -m http.server 5173`
  - Open `http://localhost:5173`

- **VS Code**
  - Use the “Live Server” extension and open `index.html`.

## Project Structure

```
Bear-Labs/
  index.html       # Home + Projects grid
  contact.html     # Contact form (mailto)
  styles.css       # Global styles + responsive layout
  script.js        # Smooth scrolling for anchor links
```

## Customization

- **Update project cards**: edit the `<section id="projects">` grid in [index.html](index.html).
- **Update styling**: change theme colors in `:root` inside [styles.css](styles.css).
- **Update avatar**: replace the `img.avatar` URL in [index.html](index.html).
- **Update contact email**: replace the email address in [contact.html](contact.html) (`mailto:` link and the form submit handler).

## Contact

- Email: `atharvamahabal8@gmail.com`
