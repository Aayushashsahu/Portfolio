## 2024-11-20 - Explicit Form Label Bindings
**Learning:** Custom `.fg` form groups without explicit `for` and `id` bindings fail to programmatically associate labels with inputs for screen readers, reducing accessibility and usability.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between the `<label class="flabel">` and `<input class="finput">` in custom form patterns.
