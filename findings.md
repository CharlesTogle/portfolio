# UI/UX Findings

## 1. Title bar text color — LOW CONTRAST ❌
**Finding:** `charles@portfolio: ~` label uses `var(--dim)` (#4b4466 dark), nearly invisible against the terminal background.
**Fix:** Use `var(--text)` with slight opacity for readability while keeping the aesthetic.
**Status:** Fixed ✅

## 2. Header not visually solid ❌
**Finding:** Title bar looks flat — no visual weight or identity. Feels like it blends in.
**Fix:** Add subtle gradient background + slightly stronger border to give the header more presence.
**Status:** Fixed ✅

## 3. No logo ❌
**Finding:** No favicon, no brand mark. Tab shows blank icon, title bar is anonymous.
**Fix:** Add inline SVG favicon + logo mark (◆ CT) inside the title bar.
**Status:** Fixed ✅

## 4. "Claude Code" stigma in AI Tools ❌
**Finding:** Reviewer noted stigma around listing Claude Code as a skill. Suggestion: reframe as broader AI dev tooling.
**Fix:** Replace "Claude Code" with "Cursor" in both AI Tools skill row and neofetch Editor field.
**Status:** Fixed ✅

## 5. No projects section ⚠️
**Finding:** Reviewer wants projects shown. Currently only experience entries exist.
**Fix:** Needs content from user — what projects to showcase, links, descriptions.
**Status:** Pending (needs user input)

## 6. Navbar suggestion ⚠️
**Finding:** Reviewer suggested a navbar for nav actions and responsiveness. Acknowledged this is optional for a single-page layout.
**Fix:** Optional — user's call.
**Status:** Pending (user's choice)
