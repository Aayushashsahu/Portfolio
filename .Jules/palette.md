## 2024-05-18 - Form Label Accessibility
**Learning:** Found that the contact form relied on visual proximity between `<label>` and `<input>` elements rather than proper programmatic association via `for` and `id` attributes. This breaks screen reader functionality and prevents clicking labels to focus inputs.
**Action:** Always ensure `<label>` elements have a `for` attribute that strictly matches the `id` of their corresponding form control, and add `required` attributes to enforce basic client-side validation.
