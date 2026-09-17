## 2024-05-24 - Form Label Connectivity
**Learning:** The application uses a custom `.fg` form group pattern containing `<label class="flabel">` and `<input class="finput">`. Without explicit `for` and `id` bindings, users cannot click labels to focus inputs, and screen readers fail to associate the label with the input correctly.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between labels and inputs in custom form group components.
