## 2025-02-23 - Form Accessibility
**Learning:** Custom `.fg` form groups containing `<label class="flabel">` and `<input class="finput">` were missing explicit `for` and `id` bindings, causing screen readers to fail to associate labels with inputs.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between labels and inputs for accessible forms.
