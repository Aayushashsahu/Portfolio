## 2026-06-11 - Explicit Label Bindings for Custom Form Groups

**Learning:** Forms utilizing custom `.fg` styling containers with `<label class="flabel">` and `<input class="finput">` elements often lack implicit label-to-input association because the input is not nested within the label tag. This causes screen readers to announce inputs without context and prevents users from clicking the label to focus the input.

**Action:** Always ensure explicit `for` and `id` bindings are implemented between the `<label>` and its corresponding `<input>` or `<textarea>` when using non-nested custom form group patterns.