# Music

The official multi-page front-end website for the "Q-bi Music Education Institute" (Q比音樂教育機構), independently designed and developed by myself. This project simulates a complete brand presence for a music education organization — covering the institute's brand story, taught instruments, classroom locations, group activities, charity programs, public classes, member portal, and founder introduction.

---

## Overview

The website is built using only the three core front-end technologies (HTML / CSS / JavaScript), with no front-end framework dependencies (Bootstrap is only referenced via CDN on a single activity page for grid utilities). The design goal is to present the full information architecture that a real music education brand needs externally, while keeping consistent navigation, typography, and visual identity across all pages.

- A pure static website that can be opened directly in any browser via `index.html`.
- Semantic HTML with one dedicated CSS file per page for clean separation of concerns.
- All image assets organized under the `image/` directory (with `instruments/` and `welfare/` subfolders).
- Embeds Google Maps on the classroom page to display physical location.

---

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Bootstrap 5 (CDN-only, used on the group activity page)
- Google Maps embed (classroom location)

---

## Project Structure

| File | Description |
| --- | --- |
| `index.html` | Home page with brand title, primary navigation, and two main entry sections: music classroom and group activities. |
| `news.html` | Latest news and announcements from the institute. |
| `story.html` | Brand story and history of the music education organization. |
| `instruments.html` | Showcase of all taught instruments (piano, violin, recorder, clarinet, etc.) with images and descriptions. |
| `members.html` | Member login portal with login form. |
| `class.html` | Music classroom page with city selection and a Google Maps embed of physical class locations. |
| `activity.html` | Group activities page, using a Bootstrap-based responsive layout. |
| `welfare.html` | Charity collaboration page introducing the partnership with Aitong Children's Home (艾彤兒童之家). |
| `plclass.html` | Public class demonstration and franchise recruitment information. |
| `creator.html` | Founder introduction page, linking to the teacher's portfolio / homework section. |
| `hw.html` | Portfolio / homework showcase for the founder. |
| `image/` | Image assets (instruments, activities, welfare events, profile photos, decorative icons). |

---

## How to Run

Since this is a pure static website, any browser can open it directly:

1. Download the entire project folder to your local machine.
2. Open `index.html` directly in a browser.
3. Use the top navigation bar to browse news, brand story, taught instruments, and the member portal.

To run with a local server (recommended for the full experience, including the Google Maps embed):

```bash
# Pick either command
python3 -m http.server 8000
# or
npx serve .
```

Then open `http://localhost:8000` in your browser.

---

## Highlights

- Full multi-page information architecture covering branding, education content, locations, activities, social impact, and member services.
- Consistent header / navigation / footer pattern reused across every page for unified UX.
- Lightweight, zero-build static site — no npm, no bundler, no backend required.
- Real-world content design: instrument showcase pages, charity introduction, founder profile, franchise / public class promotion, and member login form.
