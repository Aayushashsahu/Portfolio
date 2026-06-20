## 2026-06-20 - Explicit Label Associations
**Learning:** Custom form elements using generic tags without native wrappers often miss implicit label associations, causing screen readers and click-to-focus behaviors to fail.
**Action:** Always explicitly bind `<label for="id">` to `<input id="id">`, especially in custom implementations like `.fg` component patterns.
