## 2026-06-02 - Added Explicit Label Associations to Form Elements
**Learning:** Found that custom `.fg` form groups lacked explicit `for` and `id` bindings, causing poor screen reader accessibility for form inputs. This is a crucial accessibility issue for any custom form elements.
**Action:** Always ensure that custom form groups have a 1-to-1 explicit binding between labels and inputs using `for` and `id` attributes, even if they are visually close or structurally grouped.
