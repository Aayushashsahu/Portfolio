## 2026-05-19 - Form Label Associations
**Learning:** In hand-written HTML forms without a web framework, form labels are often left unassociated with their inputs via the `for` and `id` attributes. This breaks the expected behavior where clicking the label focuses the input, which is particularly bad for accessibility and mobile users.
**Action:** Always verify that custom form components use explicit `for` and `id` relationships.
