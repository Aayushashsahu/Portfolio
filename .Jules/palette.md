## 2024-10-24 - Form Label Bindings
**Learning:** Custom `.fg` form group components were missing explicit `for` and `id` bindings, causing screen readers to fail at associating labels with inputs.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between labels and inputs/textareas, and use `required` for mandatory fields.
