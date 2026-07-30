## 2024-11-20 - Form Accessibility in Custom Components
**Learning:** The application uses a custom `.fg` form group pattern containing `<label class="flabel">` and `<input class="finput">`. Without explicit `for` and `id` bindings, screen readers cannot reliably associate the label text with the input field, which violates WCAG guidelines for form accessibility.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between the labels and inputs across all form groups.
