# Sir Murtaza Zai · Economics website

A multi-page website for Sir Murtaza Zai: O Level, IGCSE and A Level Economics, Zai Institute, Karachi. Every page is one self-contained HTML file, and every file sits in one flat folder, with no asset sub-folders.

## Files

| File | What it is |
|---|---|
| `index.html` | Home. Contains: <ul><li>frameless hero with a live 3D supply & demand scene and an economy landscape</li><li>key figures</li><li>a pinned "headline → diagram" story with an AD/AS diagram that builds as you scroll</li><li>course covers</li><li>a live supply & demand studio with 9 market events</li><li>a rail of the diagrams that carry the marks</li><li>the syllabus mapped as one economy</li><li>a career timeline</li><li>study tools and campuses</li></ul> |
| `courses.html` | O Level 2281 (current vs 2027 format), AS & A Level 9708, IGCSE 0455, and how the course runs |
| `syllabus.html` | Every topic, unit by unit, for 2281, 0455 and 9708, with key points, key terms, formulas and a progress tracker |
| `past-papers.html` | 2281, 0455 and 9708 question papers + mark schemes, attempt tracker with scores, exam timer and focus mode |
| `lab.html` | Econ Lab: <ul><li>supply & demand (9 events)</li><li>elasticity (PED, PES, YED, XED)</li><li>an interactive PPC</li><li>a macro calculator (inflation, unemployment, GDP per head, growth, multiplier)</li><li>key-term flashcards and quiz</li></ul> |
| `notes.html` | Notes store with cart and WhatsApp checkout |
| `about.html` | About Sir Murtaza, his education and where he teaches |
| `contact.html` | Enrolment form that opens WhatsApp, contacts, FAQ |
| `404.html` | Not-found page |
| `murtaza-zai.webp` | Portrait cutout (transparent background) |
| `murtaza-zai.jpg` | Share image for WhatsApp and social previews (1200×630) |
| `vercel.json`, `robots.txt`, `sitemap.xml` | Hosting and search files |

## Check these before going live

1. **WhatsApp number.** The site uses 0324 202 0175 (+92 324 2020175), the contact listed on the @zai.institute Instagram profile. To change it, find and replace `923242020175` across the folder; the display text is `0324 202 0175`.
2. **Facts.** These come from public search results: 18+ years teaching, MBA (Supply Chain Management) SZABIST, Master's in Economics University of Karachi, Zai Institute at Boat Basin and Bahadurabad, and 9.7K Instagram followers.
   - **Career timeline:** Credo "c. 2017" and Zai Institute "c. 2022" are approximate. They are dated from social posts, so please confirm them with him.
   - **Dated entries:** Sceptre 2018, Roots Millennium 2019, Southshore 2020 and Indus University 2025 are dated from those institutions' own posts.
3. **Notes prices and titles** are demo values. Search for `PRODUCTS` in any page.
4. **Photo.** The only available photo is low resolution. Replace `murtaza-zai.webp` with a sharper cutout (transparent PNG/WebP, about 1000×1100) for a crisper hero.
5. **Domain.** `sitemap.xml`, `robots.txt` and each page's `<head>` use `https://sirmurtazazai.vercel.app`. Change these if you use another domain.

Each page carries its own copy of the shared code, so a change like the phone number must be made in every HTML file. A find-and-replace across the folder does it in one go.

## Notes on content

- The interest-rate headline on the home page is a clearly labelled practice example, not a real news report. The Lab's starting macro figures are round practice numbers.
- Key-term definitions are standard textbook wording, not quoted from Cambridge.
- Past papers open from PapaCambridge's public archive, in the format of their year. Years are limited to the current paper format: 2281 and 0455 from 2020, 9708 from 2023. The 2027 O Level and IGCSE format is shown on the Courses page, and the custom timer can be set to its new lengths.
- Progress (tracker, ticked topics, known key terms, cart, theme, sound) is saved in the visitor's own browser only.

## Deploy

- **Vercel:** drag the folder into vercel.com/new, or run `vercel` inside it. `vercel.json` gives clean URLs.
- **Netlify / GitHub Pages / any host:** upload the folder as is. There is no build step.

## Sources

- Cambridge O Level Economics 2281 syllabus 2027–2029: https://www.cambridgeinternational.org/Images/718206-2027-2029-syllabus.pdf
- Cambridge O Level Economics 2281 syllabus 2026: https://www.cambridgeinternational.org/Images/697295-2026-syllabus.pdf
- Cambridge IGCSE Economics 0455 syllabus 2027–2029: https://www.cambridgeinternational.org/Images/718148-2027-2029-syllabus.pdf
- Cambridge International AS & A Level Economics 9708 syllabus 2026–2028: https://www.cambridgeinternational.org/Images/697423-2026-2028-syllabus.pdf
