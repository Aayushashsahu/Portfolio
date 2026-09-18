## 2024-05-15 - Form Label A11y
**Learning:** Found custom `.fg` form groups lacking explicit `for` and `id` bindings between labels and inputs, which harms screen reader accessibility and click targets.
**Action:** Always ensure explicit `for` and `id` attributes connect labels to inputs, especially in custom UI patterns without semantic wrapper behaviors.
