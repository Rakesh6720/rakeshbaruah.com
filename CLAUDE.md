# CLAUDE.md
# rakeshbaruah.com – Author Website Specification

## Purpose

This website is a minimalist professional presence for playwright and fiction writer Rakesh Baruah.

Its purpose is:
- To signal seriousness and focus.
- To provide clean access to selected writing samples.
- To support outreach to theaters, literary journals, and collaborators.
- To avoid overexposure, self-promotion, or branding excess.

This is not:
- A personal blog.
- A tech portfolio.
- A startup landing page.
- A marketing-heavy platform.

Restraint is the guiding principle.

---

## Core Identity

Rakesh Baruah is a Milwaukee-based writer whose work explores power, media, institutions, and moral fracture in contemporary America.

The site should feel:
- Quiet
- Confident
- Literate
- Institutional
- Uncluttered

No hype language.
No promotional adjectives.
No inflated claims.

---

## Site Architecture

Single domain.

Primary navigation:

- Home
- Plays
- Fiction
- Contact

No additional sections unless work volume expands significantly.

---

## Homepage

### Structure

Header:
- Rakesh Baruah
- Writer
- Milwaukee, WI

Short identity paragraph (2–3 sentences max).

Featured Work section:
- Tyrant (full-length play)
- 2–3 sentence description
- Link to excerpt PDF
- "Full script available upon request"

No images required.
No headshot required.
No banner graphics.

White space is preferred over decoration.

---

## Plays Page

### Featured Work

**Tyrant**
Full-Length Play
Approx. runtime listed
Cast size listed

Short logline (tight, concrete, not thematic abstraction).

Links:
- Download 12-page excerpt (PDF)
- Full script available upon request

Optional section:
Other works in development (titles only, no PDFs).

Do not post full scripts publicly.

---

## Fiction Page

Minimal listing.

Short paragraph describing thematic focus.

List 2–3 stories:
- Title
- Format (short story, novella, etc.)
- Publication status if applicable

No full-text uploads unless published and rights allow.

---

## Tone Guidelines

Language must be:
- Direct
- Clear
- Professional
- Understated

Avoid:
- "Urgent," "timely," "gripping," "award-winning," etc.
- Mission statements
- Manifestos
- Political slogans

This is a writer's site, not a campaign.

---

## Design Constraints

- Black text on white background.
- One serif font (e.g., Garamond, Georgia, Times).
- Generous margins.
- No animations.
- No auto-playing media.
- No popups.

PDF downloads must:
- Be cleanly formatted.
- Include name and contact info.
- Exclude draft numbers.
- Exclude watermarks.

---

## Technical Stack

- **Framework:** None. Hand-written HTML and CSS only. No JavaScript unless absolutely necessary.
- **Build step:** None. Files are served as-is.
- **Hosting:** GitHub Pages, served from the `main` branch.
- **Domain:** rakeshbaruah.com (configured via GitHub Pages custom domain settings).
- **CI/CD:** Push to `main` triggers automatic GitHub Pages deployment. No additional build pipeline needed.
- **Repository:** Single repo containing all site files. Public or private per preference.

No frameworks. No bundlers. No package.json. No node_modules.
The tech stack matches the design philosophy: nothing unnecessary.

---

## Project Structure

```
/
├── index.html
├── plays.html
├── fiction.html
├── contact.html
├── css/
│   └── style.css
├── pdf/
│   ├── Tyrant_Excerpt.pdf
│   └── (future excerpts)
├── CNAME
└── CLAUDE.md
```

---

## File Management

Maintain:

/pdf
  - Tyrant_Excerpt.pdf
  - OtherWorks_Excerpt.pdf (if added later)

Keep filenames professional and simple.

---

## Future Expansion Rules

Do not expand site sections unless one of the following occurs:

- A production is mounted.
- A play receives institutional development.
- A story is published in a recognized venue.
- Representation is secured.

Expansion should be additive, not redesign-oriented.

---

## Strategic Positioning

The site should signal:

"Milwaukee-based playwright developing nationally ambitious work."

It should never feel:
- Local-only.
- Hobbyist.
- Startup-adjacent.
- Overproduced.

Understatement = authority.

---

## Final Guiding Principle

If unsure whether to add something:
Do not add it.

Restraint communicates confidence.
