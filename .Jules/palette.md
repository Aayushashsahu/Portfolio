## 2024-05-24 - Explicit Form Label Bindings
**Learning:** In custom `.fg` form groups, implicit label association is insufficient for screen readers and reduces click targets for pointer events.
**Action:** Always implement explicit `for` and `id` bindings between `<label class="flabel">` and `<input class="finput">` elements to ensure full accessibility and improved UX.