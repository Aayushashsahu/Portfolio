## 2024-05-30 - Added explicit for/id bindings to form fields
**Learning:** Custom `.fg` form groups with `<label>` and `<input>` missing explicit `for` and `id` bindings disrupt accessibility, preventing screen readers from associating labels and preventing click-to-focus behavior.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between labels and inputs, even in custom styled form groups.
