Copilot instructions for this project

Purpose
-------
This file records persistent editing and style rules for AI assistants working on this repository.

Project rules
-------------
- Use the Bootstrap framework as the primary UI framework. (เราใช้ Bootstrap framework เป็นหลัก)
- Put all custom CSS in separate .css files — do not use inline `style` attributes or long `<style>` blocks inside HTML files. (เวลาใช้ CSS ให้ใช้เป็นไฟล์แยก)
- Prefer linking a single project stylesheet (e.g. `styles.css`) from the HTML `<head>`; keep Bootstrap includes (CDN or local) intact unless the user asks to change them.
- Keep CSS modular and scoped by filename (page-specific styles in separate files when appropriate).

Scope and enforcement
---------------------
These rules apply to all HTML/CSS edits across the `bootstrap/` folder and related pages. Treat them as hard defaults; ask the user before making exceptions.

Examples (prompts)
------------------
- "Generate the HTML for a responsive landing section using Bootstrap utilities; put any custom CSS in `styles.css` and link it in the head."
- "Refactor inline styles into a new file `landing.css` and update the page head to load it after `styles.css`."

How to iterate
--------------
1. Draft changes following the rules above.
2. If a rule seems to block a necessary change, ask the user before overriding.
3. Suggest creating additional instruction files if more granular rules are needed (per-component guidance).

Next actions for you
--------------------
- Tell me if these rules should apply only to some files or the whole repo.
- If you'd like, I can also create a short checklist or linting guidance to enforce these rules automatically.
