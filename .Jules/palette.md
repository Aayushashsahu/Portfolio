## 2024-10-24 - Form Label Associations
**Learning:** The application's custom `.fg` form group pattern (containing `<label class="flabel">` and `<input class="finput">`) lacks explicit `for` and `id` bindings by default, causing accessibility issues for screen reader users who cannot associate labels with their inputs.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between the labels and inputs in the `.fg` pattern.
