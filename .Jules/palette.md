## 2024-05-15 - Explicit Form Bindings for Accessibility
**Learning:** Found that custom form components without explicit `for` and `id` bindings (relying solely on proximity or visual layout) break accessibility for screen readers and disrupt the user experience, particularly for keyboard navigation and focus states.
**Action:** Implemented explicit `for` and `id` bindings between `<label>` and `<input>`/`<textarea>` elements in the contact form to ensure screen reader friendliness and proper focus management without altering the visual design or adding custom CSS.
