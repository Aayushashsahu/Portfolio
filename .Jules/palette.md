## 2024-05-18 - Form Label Accessibility in Custom Form Groups
**Learning:** Custom `.fg` form groups with `.flabel` and `.finput`/`.ftarea` classes often lack explicit `for` and `id` bindings. This breaks screen reader association and means clicking the label doesn't focus the input.
**Action:** Always verify that `<label>` elements have a `for` attribute matching the `id` of their corresponding `<input>` or `<textarea>`, especially in custom form group implementations.
