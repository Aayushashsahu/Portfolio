## 2026-08-18 - Form Label Accessibility
**Learning:** The application uses a custom `.fg` form group pattern containing `<label class="flabel">` and `<input class="finput">`. These elements lacked explicit `for` and `id` bindings, causing screen readers to improperly associate labels with input fields.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between labels and inputs when using custom form component patterns to ensure robust accessibility.
