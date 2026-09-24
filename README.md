# IB Physics Revision

Student-facing revision aids for IB Diploma Physics, published as a GitHub Pages site.

**Live site:** https://vcanela.github.io/ib-physics-revision/

## What's here

- **`index.html`** — the landing page students open first; links to everything below.
- **`worksheets/`** — 33 sheets as PDFs with worked answers attached, plus a themed index: 24 topic warm-ups (one per syllabus topic) and 9 for Paper 1B (three full data-analysis questions and six skill drills).
- **`simulations/`** — 15 single-concept interactive simulations across Themes A to E, with their own themed index.
- **`guides/`** — Exam Craft, the Trap Field Guide (20 traps, 3 practice questions each) and the Concept Cards.
- **`reading/`** — wider reading, currently *Women Who Changed Physics*.

The Pace Trainer is linked from the Tools section but lives in its own repo and deploy: https://vcanela.github.io/pace-trainer/

Every HTML file is self-contained: no dependencies, no build step. Open any of them directly in a browser, or copy one and share it.

## Deploying updates

Served by GitHub Pages from the `main` branch, root folder. Commit to `main` and push; the site updates within a minute or two.

## Source and provenance

These resources are authored in a separate private workbench repo (`IB-revision-ideas`), which holds the planning documents, the question analysis and the worksheet LaTeX sources. The copies here are the published versions; when a resource is improved in one place, the change is copied to the other so both stay in step.

The worksheets are rebuilt from source with `worksheets/build-pdfs.sh` in the workbench repo, which produces the answers-included version by default. Copy the resulting PDFs into `worksheets/` here to update them.

Deliberately **not** published: the paper-anatomy teacher briefing (it maps the structure of papers used as a school mock), the question bank and cloning process, and any IB or textbook material that is not ours to redistribute.
