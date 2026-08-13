## 2024-08-13 - Explicit Form Label Bindings
**Learning:** Even visually adjacent labels (`.flabel`) in custom form groups (`.fg`) are not automatically associated with their inputs (`.finput`) by screen readers without explicit `for` and `id` bindings. This causes screen readers to read inputs without context.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between labels and inputs in custom `.fg` form group patterns.
