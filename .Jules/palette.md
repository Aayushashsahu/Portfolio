## 2024-05-24 - Form Input Label Association
**Learning:** Missing explicit `for` and `id` associations in custom `.fg` form groups prevents screen readers from correctly announcing form labels, degrading accessibility.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between `<label class="flabel">` and `<input class="finput">` in the `.fg` pattern.
