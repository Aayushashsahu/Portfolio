## 2024-05-24 - Form Label Bindings
**Learning:** In custom `.fg` form group patterns, inputs and textareas lack explicit `id` attributes and labels lack `for` attributes, which prevents screen readers from associating the label with the input and clicking the label from focusing the input.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between the labels and inputs.