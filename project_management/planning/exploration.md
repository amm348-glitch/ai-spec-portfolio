# Phase 0 — Exploration

## Goal
I am building a personal portfolio site to demonstrate spec-driven development with AI.

## Audience
Primary audience: course instructor  
Secondary audience: future employers or reviewers

## Constraints
- Static site (HTML/CSS)
- Hosted on GitHub Pages
- Minimal complexity
- Short timeline
- Focus on process over polish

## Success Criteria
- Deployed and accessible website
- Clear documentation of exploration → spec → sprints
- No unnecessary features or scope creep

---

## Design Direction Exploration
### Option 1 — Technical Blueprint (Minimalist Utility)

This style mimics a high-end documentation site (e.g., Stripe or Vercel docs). It prioritizes clarity, structure, and systematic thinking over decorative visuals.

**Professional Signal:**  
“I value standards, documentation, and treating the spec as the source of truth.”

**Bad Fit:**  
If the goal is expressive branding, heavy motion, or artistic visuals.

**Non-Negotiable Rules:**
- **Typography:** Sans-serif body font (Inter or System UI); monospace (JetBrains Mono) for metadata, specs, and labels
- **Color:** Strict grayscale palette with exactly one accent color used only for CTAs and status indicators
- **Layout:** Fully responsive grid with consistent spacing based on 8px increments
- **Spacing:** Tight spacing for related information; large separation between conceptual sections
- **Components:** Card-based layout using subtle 1px borders instead of shadows

**Layout Patterns:**
- **Sidebar Layout:** Fixed left navigation for phases (Spec → Prompt → Code → Result)
- **Split-Pane Layout:** Sticky spec or metadata on the left with scrollable content on the right

---

### Option 2 — Terminal Terminal (Low-Level Authority)

A refined, text-forward, terminal-inspired interface focused on linear flow and precision. Treats prompts and outputs as first-class artifacts.

**Professional Signal:**  
“I am comfortable close to the machine and treat AI interaction like code, not magic.”

**Bad Fit:**  
Highly visual portfolios or projects that rely on rich imagery and UI demos.

**Non-Negotiable Rules:**
- **Typography:** 100% monospace across the entire site
- **Color:** Dark background (e.g., #0F172A) with high-contrast text
- **Layout:** Single-column vertical flow resembling terminal history or git logs
- **Spacing:** Narrow line width (max ~80 characters) for readability
- **Components:** Code blocks as the primary container for content, prompts, and outputs

**Layout Patterns:**
- **Step-Through Timeline:** Vertical progression through development phases
- **Command-Line Hero:** Header styled like a terminal prompt (e.g., `ai-dev --project "portfolio"`)

---

### Option 3 — Swiss Brutalist (Structural Clarity)

Bold, grid-heavy, and unapologetically structured. Emphasizes hierarchy, alignment, and visible systems.

**Professional Signal:**  
“I have strong attention to detail and think in terms of systems and structure.”

**Bad Fit:**  
Very minimal content; the style can feel empty without enough information density.

**Non-Negotiable Rules:**
- **Typography:** Large, bold neo-grotesque fonts (Helvetica, Roboto) for headers
- **Color:** High-contrast black and white with a single warning/highlight color
- **Layout:** Strong visible grids with borders dividing sections
- **Spacing:** Minimal margins; separation handled by lines and boxes
- **Components:** Heavy use of tables to compare inputs vs outputs

**Layout Patterns:**
- **Bento Grid:** Multi-sized boxes for tools, prompts, results, and artifacts
- **Alternating Z-Pattern:** Large text blocks alternating sides with diagrams or tables

---
## Design Direction Exploration
### Chosen Design Direction

**Technical Blueprint (Minimalist Utility)**

**Reason for choice:**
- Instructor-first audience values clarity and structure
- Mirrors professional documentation environments (GitHub, API docs)
- Aligns strongly with spec-driven development principles
- Lowest risk of visual drift
- Simple to implement and maintain on GitHub Pages
---

## Content Exploration
### Proposed Minimum Viable Information Architecture (MVIA)

**Approach:** Single-page “Technical Whitepaper” style (documentation-first), with optional project archive later.

**Page(s):**
- **Home (single page)** with sections:
  1. **Header / Metadata**
     - Name + title (e.g., “Student Developer | AI-Augmented Workflows”)
     - 1-sentence thesis on spec-driven development
     - Links: GitHub, LinkedIn, Resume (PDF), Email
     - **Receipts:** direct links to repo + deployed site
  2. **Methodology (How I Work)**
     - 3-step flow: Spec → Prompt → Audit (short explanation)
     - **Receipts:** link to `/project_management/planning/spec.md` (later) + sprint docs
  3. **Featured Project Case Study (1 project minimum)**
     - Use the “Spec-to-Ship” template below
     - **Receipts:** links to spec, commits, screenshots, deploy URL
  4. **Toolbox / Stack**
     - Table: Tools used (HTML/CSS, GitHub Pages, AI tools), why chosen
     - **Receipts:** repo folder links, deployment settings screenshot (optional)
  5. **Footer**
     - “Built with [stack] | Last updated: [date]”
     - **Receipts:** last commit date, deploy URL

---

### Case Study Template (Spec-to-Ship Format)

**Section 1 — Brief & Constraints**
- Problem: what you built + why
- Constraints: timeline, tools, scope limits
- Spec: link to the written spec file
- **Receipts:** link to spec doc + sprint plan

**Section 2 — AI Orchestration (Process Evidence)**
- Prompt strategy: what you asked AI to do (draft, critique, refactor)
- Iteration log: what changed after critique (2–4 bullets)
- **Receipts:** key prompt snippets in the repo (or summarized notes), commit links showing changes

**Section 3 — Result & Technical Audit**
- Result: screenshots (or short GIF)
- Quality checks: Lighthouse score OR “no console errors” OR “validated on mobile + desktop”
- **Receipts:** live demo URL + repo link + final commit hash/tag

**Section 4 — Reflection (Instructor-Focused)**
- What I learned about spec-driven development + AI
- What I would change in the spec next time
- Future roadmap (2–4 bullets)
- **Receipts:** roadmap bullets + references to issues/todos (optional)

---

### Evidence / Receipts Checklist

- **Requirements proof:** link to `spec.md`
- **Workflow proof:** sprint docs + commit history
- **Build proof:** screenshots + deployed GitHub Pages link
- **Validation proof:** checklist (“mobile/desktop ok, links ok, no console errors”)
---

## Tech Exploration
Stack options considered:
Chosen stack:
Reason:
