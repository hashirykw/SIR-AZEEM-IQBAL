# Sir Azeem Iqbal · Sociology & Psychology website

A multi-page website for Sir Azeem Iqbal: O Level Sociology 2251, AS & A Level Sociology 9699 and AS & A Level Psychology 9990, Karachi and online. Every page is one self-contained HTML file in one flat folder: no CSS or JS files, no asset sub-folders.

## Files

| File | What it is |
|---|---|
| `index.html` | Home: question hero with portrait and a live 3D social network, key figures, the pinned "debate scale" (how a 26-mark essay is weighed, AO1 → AO3), course covers, the five-perspective lens, the 12 core studies rail, the Sociology–Psychology Venn, teaching section, study tools |
| `courses.html` | 2251, 9699 and 9990: every paper with time, marks and weighting, assessment objectives, what's coming (9699 new syllabus in 2029) |
| `syllabus.html` | Every topic for 2251, 9699 and 9990 with key points, key terms, the perspectives and core-study details, plus a progress tracker |
| `past-papers.html` | 2251 (2025–26), 9699 and 9990 (2024–26) question papers + mark schemes + examiner reports, attempt tracker, exam timer, focus mode |
| `lab.html` | Mind Lab: perspectives side by side, sampling simulator, hypothesis builder, descriptive statistics, core study cards and quiz, key-term flashcards |
| `notes.html` | Notes store with cart |
| `about.html` | About Sir Azeem and where he teaches |
| `contact.html` | Enrolment form, contacts, FAQ |
| `404.html` | Not-found page |
| `vercel.json`, `robots.txt`, `sitemap.xml` | Hosting and search files |

## Do these before going live

1. **Add his photo.** Save a background-removed portrait as `azeem-iqbal.webp` (transparent PNG converted to WebP, about 1000 × 1100) in this folder. The home and about pages pick it up automatically and show it frameless. Until then they show an "Azeem Iqbal" monogram. Add `azeem-iqbal.jpg` (1200 × 630) for the WhatsApp / social share preview.
2. **WhatsApp number.** No public number was found, so every "message" button currently copies the message and opens an Instagram DM to @socio_and_psych_by_azeemiqbal. To switch the whole site to WhatsApp, find `const WA=""` in every HTML file and put his number in, e.g. `const WA="923001234567", WA_DISPLAY="0300 123 4567"`.
3. **Notes prices and titles** are demo values. Search for `PRODUCTS` in any page.
4. **Facebook link** goes to a Facebook search for "Sociology-Psychology by Azeem Iqbal". Replace it with the page's real address if you have it.
5. **Domain.** `sitemap.xml`, `robots.txt` and each page's `<head>` use `https://sirazeemiqbal.vercel.app`.

Each page carries its own copy of the shared code, so a change like the WhatsApp number must be made in every HTML file. A find-and-replace across the folder does it in one go.

## Content notes

- Facts used: teaches O/A Level Sociology and A Level Psychology in Karachi; A Level faculty at Whales College (AS Sociology lectures on its YouTube channel); online courses on LearnedGuys, including a 9699 A2 live class for May/June 2027; Facebook page "Sociology-Psychology by Azeem Iqbal" (1.5K+ followers); the MnA EdTech introduction describing his humour. Confirm anything else with him.
- The practice essay question, key-term definitions, perspective summaries and core-study summaries are study notes, not Cambridge wording.
- Past papers open from PapaCambridge's public archive. Years are limited to the current paper format so durations and marks are right.
- Progress (tracker, ticked topics, known terms and studies, cart, theme, sound) is saved in the visitor's browser only.

## Deploy

Drag the folder into vercel.com/new (clean URLs via `vercel.json`), or upload it to any static host. No build step.

## Sources

- Cambridge O Level Sociology 2251 syllabus 2025–2027: https://www.cambridgeinternational.org/Images/662478-2025-2027-syllabus.pdf
- Cambridge O Level Sociology 2251 syllabus 2028–2030: https://www.cambridgeinternational.org/Images/744857-2028-2030-syllabus.pdf
- Cambridge International AS & A Level Sociology 9699 syllabus 2024–2026: https://www.cambridgeinternational.org/Images/636099-2024-2026-syllabus.pdf
- Cambridge International AS & A Level Psychology 9990 syllabus 2024–2026: https://www.cambridgeinternational.org/Images/634461-2024-2026-syllabus.pdf
- Cambridge International AS & A Level Psychology 9990 syllabus 2027: https://www.cambridgeinternational.org/Images/721433-2027-syllabus.pdf
- Cambridge syllabus changes list: https://www.cambridgeinternational.org/Images/663781-syllabus-changes-international-.pdf
