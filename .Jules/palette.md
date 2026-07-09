## 2024-10-25 - Explicit Form Label Bindings
**Learning:** Custom form group patterns (like `.fg` with `<label>` and `<input>` elements) often omit explicit `for` and `id` bindings, which breaks screen reader support and prevents clicking the label to focus the input.
**Action:** Always verify that `<label>` elements have a `for` attribute that strictly matches the `id` of their corresponding input element, especially in custom markup structures.
