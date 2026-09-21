## 2024-05-24 - Form Label Association
**Learning:** The custom `.fg` form group pattern containing `<label class="flabel">` and `<input class="finput">` elements lacked explicit `for` and `id` bindings, preventing users from clicking labels to focus inputs and hurting accessibility.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between labels and inputs in custom form groups.
