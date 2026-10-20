---
tags:
  - appearance
  - scroll_bar
---
# `enable_scroll_bar`

Enable the scrollbar. Upstream disables it by default; Pebble enables a subtle
scrollbar by default to make long scrollback easier to navigate.
It will occupy the right window padding space.

If right padding is set to 0 then it will be increased to a single cell width.

```lua
config.enable_scroll_bar = true
```

