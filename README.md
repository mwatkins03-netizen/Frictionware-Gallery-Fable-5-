# Frictionware

**Technology that preserves productive difficulty.**

An interactive detective-style evidence board showcasing the case files of Marc Watkins — small web experiences for AI literacy, literature, and the classroom. Built as a single-file Three.js scene: a rendered corkboard, hand-drawn pinned notes, and living red-string connections simulated with Verlet rope physics.

**Live experiences pinned to the board:**

| Case | Project | Link |
|---|---|---|
| 001 | Big Two-Hearted River | https://bigtwoheartedriver.netlify.app/ |
| 002 | My Mother Is a Fish (Listening Table) | https://my-mother-is-a-fish.netlify.app/ |
| 003 | I Have No Mouth | https://i-have-no-mouth.netlify.app/ |
| 004 | AI Learning Studio | https://ai-learning-studio.netlify.app/ |
| 005 | Nightfall: The Observatory Problem | https://nightfall-observatory-problem.netlify.app/ |
| 006 | The AI Midway | https://prototype-midway-fable-5.netlify.app/ |
| 007 | Omelas: The Classroom Walk | https://omelas-classroom-walk.netlify.app/ |
| 008 | Affordable Housing Simulator | https://mwatkins03-netizen.github.io/Affordable-Housing-Simulator-Fable-5-/ |

## What is Frictionware?

Frictionware uses technology to preserve the productive difficulty that learning requires.

These small, interactive experiences ask users to pause, interpret, choose, test, annotate, build, or reflect. Rather than automating intellectual work, frictionware creates structures that help people practice attention, judgment, creativity, and discernment.

Some frictionware takes the form of a game or simulation. Other examples function as reading tools, writing environments, decision-making exercises, reflective activities, or digital assignments. What connects them is a shared principle: good learning does not always come from making a task faster or easier. Sometimes technology should help us slow down, notice more, and do the work that matters.

## Using the board

- **Drag** the cork to pan, **scroll** to zoom, **grab a pinned note** to move it — the threads stretch, whip, and settle with real physics
- **Click a note** to open its case file: description, live embedded preview, and a link to the site
- **Case Index** sidebar filters by category; **Guided Tour** walks the camera pin to pin
- Full keyboard navigation (arrow keys + Enter), reduced-motion support, and a semantic fallback list for screen readers

## Running / deploying

No build step. Everything is static; Three.js loads from CDN.

- **Locally:** serve the folder (`python3 -m http.server`) and open `index.html` — opening the file directly won't work because of module/texture loading.
- **GitHub Pages:** push this folder as a repo, enable Pages on the main branch. `.nojekyll` is included.
- **Netlify:** drag the folder into the Netlify dashboard.

## AI disclosure

This board — and the projects pinned to it — were built by Marc Watkins in collaboration with AI (Claude). Concept, curation, pedagogy, and editorial direction are human; much of the code and visual drafting was AI-assisted and human-reviewed. Part of an ongoing practice of transparent AI use in teaching.
