## 2024-08-17 - Missing explicit label bindings in form groups
**Learning:** Custom `.fg` form group patterns containing `<label class="flabel">` and `<input class="finput">` were found without explicit `for` and `id` bindings. This breaks screen reader associations and prevents users from clicking labels to focus inputs, negatively impacting both accessibility and general UX.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between labels and inputs in custom form patterns to guarantee accessibility and better user interaction.
