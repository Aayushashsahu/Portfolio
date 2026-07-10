## 2024-05-24 - Explicit Form Bindings in Custom Component Patterns
**Learning:** While relying on custom class-based grouping patterns (like `.fg` with `.flabel` and `.finput`) helps with CSS styling, screen readers require explicit `for` and `id` attribute bindings to correctly associate labels with their respective form fields. Without these explicit bindings, form fields remain unlabeled to assistive technologies.
**Action:** Always ensure explicit `for` and `id` attributes are implemented when building custom form group structures, even if visual grouping is achieved via CSS.
