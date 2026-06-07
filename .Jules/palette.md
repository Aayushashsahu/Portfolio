## 2024-10-24 - Form Label Association
**Learning:** The custom `.fg` form group components in the contact section lacked explicit label-to-input associations which degrades screen reader accessibility and prevents clicking the label from focusing the input.
**Action:** Added explicit `for` attributes to `<label class="flabel">` elements and corresponding `id` attributes to `<input class="finput">` elements to ensure strict programmatic bindings.
