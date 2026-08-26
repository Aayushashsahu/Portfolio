## 2024-05-24 - Add explicit label bindings to contact form
**Learning:** Implicit label wrapping or missing `for`/`id` bindings reduces tap targets and impairs screen reader experiences. In custom UI patterns like the `.fg` form group, explicitly binding `<label for="...">` to `<input id="...">` ensures maximum accessibility without visual changes.
**Action:** Always verify that every label in a form group has an explicit `for` attribute that perfectly matches the `id` of its corresponding input field.
