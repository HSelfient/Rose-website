# ROSÉ Federation — Project Memory

## What This Is
The ROSÉ Federation is a six-company consortium building cryptographic execution proof
infrastructure for autonomous AI. The anchor entity is Selfient.xyz, led by CEO and
Co-Founder Helen Sharron. The website is deployed on GoDaddy via GitHub.

---

## The Federation Partners
1. **Selfient.xyz** — anchor entity
2. **Matric**
3. **ROKO.Network**
4. **Latitude.sh**
5. **Fortémi** — accent on the é is mandatory, always
6. **TimeBeat**

---

## Terminology — Non-Negotiable
- The consortium is the **ROSÉ Federation**. Never "Partnership," never "Alliance," never any substitute.
- **ROSÉ** always carries its accent. Never "ROSE."
- **ROSÉ** stands for: Regulated, Ordered, and Signed Execution.
- The hero headline reads exactly: *"The infrastructure with the ability to prove the work of AI agents."*
- Contact email is obfuscated in HTML source to protect against scrapers,
  but all Formspree routing delivers to: helen@selfient.com.

---

## Brand Voice
- Authoritative and analytical in tone; commercial positioning belongs last, never first.
- ROSÉ is positioned as the conclusion the evidence demands — not a vendor seeking attention.
- The audience is sophisticated: CISOs, compliance officers, enterprise technology buyers,
  financial institution leadership, and legal counsel.
- Appeal to a feminine sensibility: precise, relational, trustworthy, quietly formidable.
- Formal register. No contractions in published copy. No exclamation points.
- Grammar is held to the highest standard. When in doubt, err toward Strunk and White.
- The Oxford comma is mandatory in all copy, always.

---

## HTML Architecture
- Standalone `.html` files for all white papers — no inline modals. This is intentional,
  to prevent content loss during future edits.
- Current white paper files: `csa-analysis.html`, `whitepaper-blackbox.html`,
  `whitepaper-delay.html`, `whitepaper-euaiact.html`
- Compliance assessment tool: `compliance-assessment.html`
- Homepage: `index.html`
- PDF downloads use actual uploaded PDFs, not generated text.
  Reason: to preserve attribution of work product.

---

## Navigation Architecture — Non-Negotiable
- Every standalone page and every tool must carry the persistent site navigation header.
  No page is an island. Every page must provide a clear path back to `index.html`.
- The site navigation hamburger (☰) occupies the **top-right corner** at a fixed
  z-index above all page content, on every page without exception.
- Page-level controls (CLOSE buttons, modal dismissals, back arrows) must be placed
  at a **distinct and non-competing position** — never the same corner as the
  navigation hamburger, never the same stacking layer.
- Rule of two layers: (1) site navigation, always topmost; (2) page controls, always below.
  These two layers must never visually collide.
- All pages must be fully functional and navigable on mobile. Every section must be
  reachable and togglable from the home page on a small screen.
- Test every page at mobile viewport before considering a change complete.

---

## What To Avoid
- Do not rename the Federation or soften its identity for any reason.
- Do not drop the accent from ROSÉ or Fortémi under any circumstances.
- Do not route contact forms anywhere other than helen@selfient.com.
- Do not expose the contact email address in plain HTML source text.
- Do not generate PDFs from text when a source PDF exists.
- Do not rewrite in full when a surgical edit will serve.
- Do not produce any page that lacks a navigable return path to the homepage.

---

## Code Quality

- Before delivering any HTML, JavaScript, or CSS, flag any function, style rule, or element that is defined but has no reachable call path or selector match. Dead code is a maintenance hazard and a source of invisible bugs.
- Legal disclaimers must appear at every point where a result, score, or risk assessment is presented to the user — not only at the final results screen. If a triage result, a partial score, or any assessment output is shown, the disclaimer appears there as well.

---

## File Sourcing — Non-Negotiable

- Always work from files downloaded directly from GitHub, not from content pasted into the chat interface. Chat pastes may be truncated, stale, or behind the canonical version.
- The GitHub raw URL format is the correct source: `https://raw.githubusercontent.com/[username]/[repo]/main/[filename]`
- Claude can fetch raw GitHub URLs directly using the web tool — no manual upload required when a raw URL is provided.
- Workflow: download from GitHub → upload to Claude → Claude returns corrected file → upload back to GitHub.

---

## Mobile Navigation — Non-Negotiable

- Every page must include a fully functional mobile hamburger menu. No page is permitted to show a blank or inaccessible navigation on small screens.
- The mobile nav overlay must contain every link that the desktop nav contains — including the Assessment link and the Connect CTA. No orphaned links between desktop and mobile.
- The hamburger button (☰) must carry z-index: 200. Modal close buttons must carry z-index: 1010 — always above the hamburger, never competing with it.
- On mobile viewports, modal close buttons must shift downward (top: 4.5rem minimum) to clear the fixed nav bar. This rule applies to every modal on every page.
- When reviewing any page for mobile readiness, verify: (1) hamburger is present and functional, (2) all nav links appear in the mobile overlay, (3) no close button collides with the hamburger or nav bar.
