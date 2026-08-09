## 2024-05-24 - Form Group Accessibility Pattern
**Learning:** The application uses a custom `.fg` form group pattern containing `<label class="flabel">` and `<input class="finput">` that previously lacked explicit association.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between labels and inputs in this pattern to support screen readers and click-to-focus functionality.
