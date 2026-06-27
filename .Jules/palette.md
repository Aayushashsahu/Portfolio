## 2026-06-27 - Form Group Accessibility
**Learning:** The custom `.fg` form group pattern needs explicit `for` and `id` attributes to properly associate labels with inputs/textareas, ensuring screen readers can correctly announce the fields.
**Action:** Always ensure explicit `for` and `id` bindings are implemented when working with custom form groups like `.fg` containing `<label class="flabel">` and `<input class="finput">`.
