[README.md](https://github.com/user-attachments/files/25789322/README.md)
# ✈️ FlySidz — Personal Portfolio

> **PC Nerd · Aviation Enthusiast · Explorer**

A fully interactive, aviation-themed personal portfolio website built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies — just one file, ready to fly.

---

## 🛫 Live Demo

Deploy on [Netlify](https://netlify.com) or [Vercel](https://vercel.com) by dropping the `index.html` file directly.

---

## 📋 Features

| Feature | Description |
|---|---|
| ✈️ **Aviation Theme** | Full cockpit-inspired dark UI with HUD, runway, and animated plane |
| 🛫 **Loading Screen** | Takeoff animation before the portfolio loads |
| 📟 **ATC Ticker** | Live typewriter-style ATC clearance messages at the bottom |
| ☀️ **Day / Night Mode** | Toggle between dark cockpit and bright sky theme |
| 🔊 **Cabin Audio** | Ambient engine hum toggle |
| 🌦️ **Live Airport Weather** | METAR-style weather data for VABB, EGLL, KLAX, OMDB, YSSY |
| 🧠 **Aviation Quiz** | Random quiz pops up when clicking any social link — correct = "Positive Rate!", wrong = "Grounded!" (still redirects) |
| 📓 **Flight Log** | Virtual sim flight entries with routes, aircraft & duration |
| 🌙 **Fully Responsive** | Mobile-friendly with hamburger menu and touch-optimized layout |
| 🎯 **Custom Cursor** | Smooth lagging cursor with gold dot (desktop only) |
| 🌟 **Scroll Animations** | Sections and elements reveal on scroll |
| 📊 **Animated Skill Bars** | Skills animate into view when scrolled into frame |

---

## 🗂️ Sections

- **About Me** — Bio, 1500+ virtual flight hours, PC hardware knowledge stat
- **Skills & Tech** — PC Building, Hardware & Overclocking, System & Config, Exploring AIs
- **Hobbies & Interests** — Aviation, Flight Simulation, Plane Spotting, Travel, Aerospace Reading
- **Live Airport Weather** — METAR data viewer with airport switcher
- **Flight Log** — Captain's log of virtual sim flights
- **My Rig & Sims** — PC spec sheet (TBA) + MSFS 2020 & 2024 cards
- **Connect Here** — YouTube, Instagram, Twitch, Discord, Steam, Xbox

---

## 🚀 Deployment

### Netlify (Recommended)
1. Download `index.html`
2. Go to [netlify.com](https://netlify.com) → Sites
3. Drag and drop `index.html` onto the page
4. Your site is live instantly ✅

### Vercel
1. Create a folder e.g. `flysidz/`
2. Place `index.html` inside
3. Go to [vercel.com](https://vercel.com) → New Project → import folder
4. Deploy ✅

> ⚠️ **Important:** The file must be named `index.html` — not `portfolio.html` — otherwise the host will show a 404.

---

## 🛠️ Built With

- **HTML5** — Single file, zero build step
- **CSS3** — Custom properties, animations, grid, flexbox, media queries
- **Vanilla JavaScript** — All interactivity, no libraries
- **Google Fonts** — Orbitron, Share Tech Mono, Rajdhani
- **Web Audio API** — Cabin hum ambient sound

---

## 📁 File Structure

```
flysidz/
└── index.html    ← Everything lives here
└── README.md     ← You are here
```

---

## ✏️ Customisation

All content is in `index.html`. To personalise:

| What | Where in file |
|---|---|
| Name & bio | `<!-- About -->` section |
| Skill percentages | `data-width="XX"` on `.skill-fill` elements |
| Social links | `<!-- Connect -->` section `.contact-link` hrefs |
| PC specs | `<!-- Rig & Sims -->` spec sheet rows |
| Flight log entries | `<!-- FLIGHT LOG -->` section `.log-entry` blocks |
| METAR airports | `metarData` object in the script |
| ATC messages | `atcLines` array in the script |
| Quiz questions | `quizQuestions` array in the script |

---

## 📸 Socials

| Platform | Link |
|---|---|
| YouTube | [@flysidz](https://youtube.com/@flysidz) |
| Instagram | [flysidz](https://www.instagram.com/flysidz/) |
| Twitch | [sidz_http](https://www.twitch.tv/sidz_http) |
| Discord | [sidz3904](https://discord.gg/CTQEFuPH) |
| Steam | [sidz06](https://steamcommunity.com/id/sidz06/) |
| Xbox | [sidz777](https://www.xbox.com/en-US/play/user/sidz777) |

---

## 📄 License

This project is personal and open for inspiration. Feel free to fork and customise for your own portfolio — just don't copy it as-is and claim it as yours. ✌️

---

<p align="center">
  Designed at <strong>35,000ft</strong> · Made with ✈️ & ☕ by <strong>FlySidz</strong>
</p>
