## 2026-05-29 - Explicit Form Label Binding
**Learning:** Custom form group patterns (like `.fg` with `<label class="flabel">` and `<input class="finput">`) are often missing explicit `for`/`id` bindings because they are styled to look visually associated. Screen readers and click-to-focus accessibility require explicit DOM linkage.
**Action:** Always ensure custom form group elements have matching `for` and `id` attributes linking labels to inputs for accessibility.
