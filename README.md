## Changes from the actual sway

### Change colors for individual windows
```
*client.<class>* [global|default] <border> <background> <text> [<indicator> [<child_border>]]
```
- Nothing for per-window colors
- `global` for all windows
- `default` to remove any window specific colors

Reminder for myself : this is not a "rule", it is a client command. So if the window doesn't respect the criteria, it won't return to the default colors.
