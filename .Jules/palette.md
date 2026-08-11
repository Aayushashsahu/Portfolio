## 2026-05-26 - Explicit form label binding

**Learning:** The application uses a custom `.fg` form group pattern containing `<label class="flabel">` and `<input class="finput">` that previously lacked explicit association. This prevents screen readers from understanding which label applies to which input, and prevents users from clicking a label to focus an input.
**Action:** Always ensure explicit `for` and `id` bindings are implemented between the `<label>` and `<input>`/`<textarea>` elements within the `.fg` component pattern for full accessibility.