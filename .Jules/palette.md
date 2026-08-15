## 2025-01-20 - Explicit Form Label Bindings
**Learning:** Forms utilizing custom `.fg` component structures often omit explicit bindings between labels and inputs, hindering accessibility. Screen readers rely on explicit connections to announce fields correctly, and clicking a label should intuitively focus the associated input field.
**Action:** Always verify and implement explicit `for` and `id` bindings between `<label>` and `<input>`/`<textarea>` elements within custom form components to ensure robust keyboard and screen reader accessibility.
