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

## Content Exploration
What pages are required?  
What proof builds trust quickly?

---

## Tech Exploration
Stack options considered:
Chosen stack:
Reason:
