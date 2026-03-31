# Pocket Sounds Museum

Pocket Sounds is a digital museum exhibit about the evolution of portable music technology. The site follows the shift from cassette listening to streaming culture and is built to feel like a curated exhibition rather than a generic website.

## Museum Concept

This museum asks a simple question: **how did music become something people could carry, control, and eventually access from almost anywhere?**

The exhibit uses five turning points:
- Sony Walkman TPS-L2 (1979)
- Sony Discman D-50 (1984)
- MP3 format naming and compression breakthrough (1995)
- Apple iPod (2001)
- Spotify launch (2008)

## Target Audience

This project is for students and general visitors interested in technology, media history, design, and culture.

## Design Framework

### Design Style: Swiss
The site uses Swiss design principles:
- strong typography
- grid-based layout
- clean spacing
- limited color palette
- minimal decorative clutter

This style supports museum clarity and makes the information easy to scan.

### Cialdini Principle: Curiosity
The site uses curiosity to guide engagement. Each section leads naturally to the next technological shift, encouraging the visitor to continue through the exhibit.

### Brand Archetype: Sage
The Sage archetype shapes the site’s voice. The tone is reflective, educational, calm, and focused on helping visitors understand a larger historical pattern.

## AI Orchestration Process

This project was developed using a spec-driven workflow inspired by the course reference repository.

### Workflow
1. **Spec** — define the museum concept, page goals, and design constraints
2. **QA** — review whether the idea feels like an exhibit and not just a report
3. **Sprint** — isolate a small build scope for the first version
4. **QA** — review narrative flow, readability, and page structure
5. **Implement** — build the pages and visual system
6. **QA** — revise from the perspective of a Smithsonian-style curator

### Why this process matters
The process reduces drift, keeps the site coherent, and creates a durable record of decisions instead of relying on loose chat history.

## Reference Project Review

After reviewing the professor’s reference repository, these were the strongest ideas:

- Use **durable artifacts** instead of depending on chat memory.
- Break big ideas into **bounded sprints**.
- Use **QA passes between steps** so work does not just look finished — it is checked.
- Keep the process auditable by documenting **scope, intent, and improvement steps**.

These ideas shaped the project structure in the `docs/` folder.

## Smithsonian-Style Curator Review

The site was reviewed as if it were a digital exhibition.

### Strengths
- clear narrative arc
- focused concept
- strong educational value
- consistent visual language

### Issues noticed
- first draft was too much like a timeline summary
- needed stronger transitions between artifacts
- needed more explicit curatorial framing

### Improvements made
- added curator-style framing text
- reinforced the central theme of ownership vs. access
- separated the artifact wall from the main exhibit page
- added a dedicated process page to show development thinking

## File Structure

- `index.html` — main exhibit page
- `artifacts.html` — artifact wall with source links
- `process.html` — process explanation
- `styles.css` — visual system and layout
- `docs/` — assignment planning artifacts

## Sources / Starting Artifacts

1. Smithsonian object page for the Sony TPS-L2 Walkman
2. Sony historical material about Walkman and Discman development
3. Fraunhofer history page on MP3
4. Apple newsroom announcement for the iPod
5. Spotify company information page

## How to Run

Open `index.html` in a browser.

## GitHub Submission Notes

For class submission, upload this folder to a GitHub repository and enable GitHub Pages if required. The README already explains the museum concept, design style, brand archetype, persuasion method, and orchestration process.
