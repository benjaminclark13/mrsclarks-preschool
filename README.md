# Mrs. Clark's Pre-K Class — Room A108

A boho, preschool-friendly static website for Mrs. Clark's Pre-K class (Room
A108) at Cambridge Elementary School, South Brunswick School District, for
the 2026–2027 school year. Plain HTML/CSS/JS (no build step, no
dependencies) so it can be hosted for free on GitHub Pages.

The color palette (sage green, terracotta, mustard, dusty blue, cream) and
the italic serif headings were pulled directly from Mrs. Clark's 2026-2027
Welcome Letter so the site feels like a natural extension of it.

## What's here

- `index.html` — Home page: hero with an Email / Important Dates / Welcome
  Letter button row, a short note from Mrs. Clark (with her photo), what
  children can expect, bus riders, monthly lunch menu,
  getting-ready-for-day-one info (supplies, snack & lunch, family photo),
  and key dates
- `about.html` — About the Teacher: her full welcome-letter bio (background,
  teaching philosophy, teaching goals) plus education & experience
- `contact.html` — Contact info (email, address, phone)
- `school-hours.html` — Full day / early release / delayed opening
  schedules (general time first, then Pre-K-only drop-off/pick-up times
  underneath) and the Emergency School Closing Information link
- `dates-reminders.html` — Important dates, Important Reminders (illness
  policy, snacks & lunch, allergy info, birthday celebrations)
- `resources.html` — Quick links for families
- `assets/style.css` — All site styling (palette, fonts, layout)
- `assets/main.js` — Mobile nav toggle + active-link highlighting
- `assets/img/mrs-clark-photo.jpg` — Mrs. Clark's photo, used on the Home page
- `assets/img/bus-safety-first.jpg` — the "Safety First" seatbelt graphic,
  used in the Bus Riders section
- `assets/img/september-lunch-menu.jpg` — the September 2026 Cambridge
  Elementary lunch menu, used in the Monthly Lunch Menu section
- `assets/docs/welcome-letter-2026-2027.pdf` — the full Welcome Letter,
  linked from the Home page hero

Last year's Weekly Recap and Classroom Photos pages were removed for the new
school year, at your request. The Cougar Council flyers section was also
removed from the Home page for now — it'll be added back once you have real
flyers to share.

## What's real vs. placeholder

The teacher bio, education/experience, "What Children Can Expect," family
partnership note, snack & lunch info, family photo request, supply list
mention, the three September dates, and the School Hours schedule (full
day / early release / delayed opening, plus the Emergency School Closing
Information link) were all pulled directly from the documents you shared.
Mrs. Clark's photo, the Bus Riders safety graphic, and the September lunch
menu image on the Home page are all real.

Still placeholders, ready for the details you'll send over:

- **Monthly lunch menu image** — the September 2026 menu is up now; send
  over each new month's menu image and I'll swap it in
  (`assets/img/september-lunch-menu.jpg`).
- **Cougar Council flyers section** — removed from the Home page for now;
  send over the flyers whenever you're ready and I'll add the section back.
- **Dates & Reminders** — has the three September dates plus the Important
  Reminders (Illness, Snacks & Lunch, Allergen Aware, Birthday Celebrations);
  there's a small note inviting more dates later.
- **Resources** — the outdated 2025–2026 Cougar Council Initiatives link was
  removed; send over the 2026–2027 link whenever you have it and I'll add
  it back in.

## Editing content

Every page is a self-contained `.html` file with plain text — open any file
in a text editor, find the paragraph or heading you want to change, and edit
it directly. No build tools or npm install required.

## Publishing with GitHub Pages

1. Create a new repository on GitHub (e.g. `mrsclarks-preschool`).
2. From this folder, push it up:

   ```bash
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git branch -M main
   git push -u origin main
   ```

3. On GitHub, go to **Settings → Pages**, set the source to the `main`
   branch and `/ (root)` folder, and save.
4. Your site will be live at
   `https://<your-username>.github.io/<your-repo>/` within a minute or two.

## Local preview

Just open `index.html` in a browser — everything is plain HTML/CSS/JS with
no server or build step required. (For the cleanest experience, you can also
run a tiny local server, e.g. `python3 -m http.server`, and visit
`http://localhost:8000`.)
