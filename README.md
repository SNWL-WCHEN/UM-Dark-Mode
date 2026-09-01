# Dark Mode — Unified Management Design System

### ▶ [View the live prototype](https://snwl-wchen.github.io/UM-Dark-Mode/)

A dark mode implementation for an enterprise security management platform, built inside an existing design system rather than as a standalone visual exercise.

---

## The problem

Security operators live in these consoles, often for long shifts and frequently at odd hours. Dark mode is a real quality-of-life request in this context, not a stylistic preference. But retrofitting it into an established design system is harder than picking darker colors: every token, state, and component has to hold up, and contrast requirements do not relax just because the background changed.

## What this prototype covers

- **Token-level treatment** rather than surface-level color swaps, so the system stays coherent
- **Component states** including hover, active, disabled, and error across the existing library
- **Contrast and legibility** for dense operational data, where readability matters more than aesthetics
- **Status and alert colors** that stay distinguishable against a dark background, which is where most naive implementations break
- **Consistency with the existing light theme** so both feel like the same product

## How I approached it

I built this as a working prototype in the existing design system and component library, which is the only way to find out whether a theme actually holds up. Static mockups hide the problems. Real components under real states expose them.

The standard I held it to was whether an operator scanning a dense alert table at two in the morning could read it as easily as they could in light mode. Anything that failed that test was not done.

---

**Role:** Product Manager. I built this prototype myself to pressure-test the approach before engineering investment.

**Stack:** HTML, CSS, JavaScript

---

