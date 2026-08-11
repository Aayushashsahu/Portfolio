## 2024-03-24 - Form Field Accessibility Bindings
**Learning:** When using custom component structures (like `.fg` groups with `.flabel` and `.finput`), it's easy to overlook native HTML accessibility features like explicit `for` and `id` bindings. Screen readers rely on these associations to properly announce form fields.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between labels and inputs, especially in custom UI components where standard nesting might not be used.
