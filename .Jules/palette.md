## 2024-10-30 - Missing form labels bindings
**Learning:** The custom `.fg` form group pattern uses `<label>` and `<input>` elements but lacks explicit `for` and `id` bindings, making it difficult for screen readers to associate the label with the input field.
**Action:** Always ensure explicit `for` and `id` attributes are added to bind labels and inputs within form groups for accessibility.