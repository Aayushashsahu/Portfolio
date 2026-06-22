## 2024-06-22 - Explicit Label Bindings in Custom Form Groups
**Learning:** The application uses a custom `.fg` form group pattern with generic `flabel` and `finput` classes that previously lacked explicit screen reader associations. While visual layout implies connection, implicit wrapping wasn't used, making explicit `for`/`id` bindings critical for accessibility.
**Action:** Always verify explicit `for` and `id` bindings are implemented when encountering custom form structures like `.fg` that decouple labels from inputs structurally.
