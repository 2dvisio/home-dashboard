# Home Dashboard

Independent iPad-friendly family dashboard prototype, built as a standalone static JavaScript application. No Home Assistant required and no changes to the personal website.

## Features in version 0.1
- Responsive tablet layout and live clock
- Live weather via Open-Meteo (currently configured for Harrow, London)
- Illustrative upcoming family events
- Interactive household tasks and shopping list with browser-local storage
- Integration status for planned services

## Run it
Open `index.html` in a browser, or serve the directory locally with `python3 -m http.server 8000`.

## Next steps
1. Refine the iPad design and information hierarchy.
2. Integrate Google Calendar and Google Tasks with OAuth.
3. Add optional secured synchronisation between family members and devices.
4. Explore Alexa alternatives, noting Amazon discontinued the official Alexa List Management API.
5. Add Progressive Web App support for an app-like iPad experience.

## Important limitations
No Google credentials are used. Calendar items are demonstrations, not live data. Tasks and shopping items are saved only on the current device and are not shared or backed up. Weather uses fixed example coordinates. Hosting the site through GitHub Pages may make the dashboard publicly visible even if the repository itself is private; avoid adding personal family data until authentication and privacy are addressed.
