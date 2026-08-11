## 2024-05-21 - Native Form Elements & Accessibility

**Learning:** When inputs are constructed with raw `<div>` and `<input>`/`<textarea>` tags without a parent `<form>` or linked `<label>`s via `for`/`id`, they lose out on native browser form validations (e.g. `required`) and accessibility for screen reader navigation. Users on assistive technologies miss out on crucial context when focusing on inputs.

**Action:** Ensure all inputs are correctly wrapped in a `<form>` tag and use `<label>` tags with matching `for` and `id` attributes. Leverage native HTML5 validation constraints (like `required`, `type="email"`) before leaning into custom JavaScript solutions.