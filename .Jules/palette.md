## 2024-05-18 - Form Input Accessibility
**Learning:** The custom `.fg` form group pattern containing `<label class="flabel">` and `<input class="finput">` lacks explicit `for` and `id` bindings, which breaks screen reader accessibility for the inputs.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between labels and inputs in the custom `.fg` pattern.
