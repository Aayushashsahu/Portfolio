## 2024-05-18 - Form Accessibility Labels
**Learning:** The `.fg` form group pattern uses `<label class="flabel">` and `<input class="finput">` structure but lacks explicit association. This prevents screen readers from understanding which label corresponds to which input.
**Action:** Always add explicit `for` and `id` bindings between labels and inputs/textareas to ensure keyboard and screen reader accessibility for form fields.
