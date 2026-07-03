## 2026-07-03 - Explicit Label Bindings in Custom Forms
**Learning:** When building custom form group components (like `.fg`), it's easy to rely on visual proximity for labels, but screen readers require explicit `for` and `id` bindings between labels and inputs to announce them correctly.
**Action:** Always ensure `<label for="[id]">` and `<input id="[id]">` are explicitly paired in forms, even if they are visually grouped together.
