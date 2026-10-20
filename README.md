# Pylon Form Builder

A single-file, dependency-free redesign of the Pylon intake customizer: structure tree, live canvas with test mode, and a focused inspector.

- **Run it:** open `pylon-form-builder.html` in a browser, or serve the folder statically.
- **Stack:** one HTML file (CSS + vanilla JS). Google Fonts is the only network request.
- **State:** drafts and editor preferences autosave to `localStorage`; nothing is sent anywhere.

## What's in it

- Sections → screens → fields, with drag-to-reorder, context menus, keyboard navigation and search
- Live canvas with desktop / tablet / phone widths, zoom, click-to-select and inline title editing
- Test mode that walks the form as a borrower would, with required-field and format validation and conditional screens/fields
- Inspector: content, options, data mapping, visibility rules, per-field appearance, reusable styles
- Brand (logo upload, color with automatic contrast) and Style (scheme, font, title size/weight, corner radius)
- Form / theme / schema JSON export and import
- Undo/redo, command palette (`⌘K`), shortcuts (`?`), resizable panels, light/dark editor theme

Prototype only: publish, saved forms and the question library are simulated.
