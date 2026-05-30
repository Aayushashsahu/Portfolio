## 2024-05-18 - Explicitly Link Form Labels and Inputs
**Learning:** The custom `.fg` form group pattern containing `<label class="flabel">` and `<input class="finput">` required explicit `for` and `id` bindings to correctly associate labels with inputs, enabling screen readers to announce fields appropriately and improving click targets.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between labels and inputs, rather than relying solely on visual proximity or implicit nesting.
