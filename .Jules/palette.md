## 2024-05-18 - Form Group Accessibility Pattern
**Learning:** Discovered an accessibility issue pattern specific to this app's components, where the custom `.fg` form group pattern contains `<label class="flabel">` and `<input class="finput">` without explicit `for` and `id` bindings. This breaks screen reader associations and prevents users from clicking the label to focus the input.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between the labels and inputs in this custom `.fg` pattern.
