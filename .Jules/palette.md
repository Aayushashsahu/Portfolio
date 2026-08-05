## 2024-05-18 - Form Label Accessibility in .fg Pattern
**Learning:** Found that the custom `.fg` form group pattern containing `<label class="flabel">` and `<input class="finput">` lacked explicit `for` and `id` bindings, preventing screen readers from associating labels with inputs and breaking click-to-focus behavior.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between labels and inputs in custom form patterns.
