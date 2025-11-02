# WaxTrackr

WaxTrackr helps you keep track of waxing and maintenance for your boards (surfboards, skis, snowboards) so you always know when to re-wax, what wax you used, and how conditions affected performance.

Live demo: (host this repo with GitHub Pages and add the link here)

<!-- Add project badges here (build, license, release) -->

## Table of contents

- About
- Features
- Screenshots
- Installation
- Usage
- Development
- Contributing
- License
- Contact

## About

WaxTrackr is a lightweight web app for logging wax sessions, scheduling reminders, and storing notes and photos for each waxing event. It aims to help surfers and winter-sports enthusiasts improve performance by tracking waxing history and environmental conditions.

Key uses:
- Track wax date, wax type, and quantity
- Attach photos and notes for each session
- Record environmental conditions (temperature, water/snow type) that matter for waxing
- Get reminders when a board is due for re-waxing

## Features

- Create and manage boards (name, type, dimensions)
- Log waxing sessions with date, wax brand/type, notes, and photos
- View waxing history and sort/filter by board, date, or wax type
- Set re-wax reminders and view upcoming maintenance
- Export and backup data (CSV / JSON)
- Mobile-friendly layout for quick logging at the beach or slopes

## Screenshots

Add screenshots to the `assets/` folder and reference them below. Example:

![WaxTrackr dashboard](assets/screenshot-dashboard.png)
![Add wax session](assets/screenshot-add-session.png)

If you want, I can add sample screenshots if you provide images or point to them.

## Installation

This repository is set up as a static site (GitHub Pages friendly). To preview locally:

1. Clone the repo

```bash
git clone https://github.com/seru94/seru94.github.io.git
cd seru94.github.io
```

2. Serve it locally using a static server (examples):

```bash
# with Python 3
python3 -m http.server 8000

# or with npm http-server
npx http-server -c-1 .
```

Open http://localhost:8000 in your browser.

If this is a single-page app built with a framework (React, Vue, etc.) add framework-specific dev instructions here. Let me know which stack you used and I can add exact commands.

## Usage

- Add a board entry for each board you want to track.
- Create a waxing session and fill in the wax type, date, and notes.
- Use the dashboard to see last waxed date and upcoming reminders.

## Development

If you want me to wire up a development environment, list the framework and toolchain (React/Vite, Next.js, Astro, plain HTML/CSS/JS, etc.). For now the repo is a static site.

Recommended small improvements you might want to add next:

- Integrate a small backend (Firebase / Supabase) for persistent user data and sync across devices
- Add authentication to save per-user boards
- Add an export/import feature (CSV / JSON)

## Contributing

Contributions are welcome. Please open an issue or a pull request with a description of the change. If you'd like a contributor guide or issue templates, I can add them.

## License

This project is licensed under the MIT License — see the LICENSE file for details.

## Contact

Open issues here on GitHub or contact the maintainer at the GitHub profile: https://github.com/seru94

---

If you'd like, I can:

1. Tailor the README text to a specific target (surfboards vs skis).
2. Add live demo link and example badges.
3. Add screenshots and wiring for GitHub Pages publishing.

Tell me which of the above you'd like next and provide any app-specific details (tech stack, demo link, screenshots, or a short app description) and I'll update the README accordingly.
