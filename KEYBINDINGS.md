# Kitty Keybindings User Guide

This guide documents the custom shortcuts in my Kitty configuration. `Alt`
means the **Alt** key; hold it while pressing the other key or keys.

## Windows and splits

| Action | Shortcut |
| --- | --- |
| Open a new horizontal split in the current directory | `Alt+Enter` |
| Open a new vertical split in the current directory | `Alt+Shift+Enter` |
| Close the current window without shell-process confirmation | `Alt+W` |
| Focus the window to the left | `Alt+Shift+Left` |
| Focus the window to the right | `Alt+Shift+Right` |
| Focus the window above | `Alt+Up` |
| Focus the window below | `Alt+Down` |
| Toggle the stack layout | `Alt+Shift+Z` |
| Swap the current window with another window | `Alt+Shift+=` |

## Tabs

| Action | Shortcut |
| --- | --- |
| Open a new tab | `Alt+T` |
| Go to the previous tab | `Alt+Left` |
| Go to the next tab | `Alt+Right` |
| Go directly to tab 1–8 | `Alt+1` through `Alt+8` |
| Move the current tab left | `Ctrl+Shift+Alt+Left` |
| Move the current tab right | `Ctrl+Shift+Alt+Right` |

## Clipboard and font size

| Action | Shortcut |
| --- | --- |
| Copy the selection to the clipboard | `Alt+C` |
| Paste from the clipboard | `Alt+V` |
| Increase font size | `Alt+=` |
| Decrease font size | `Alt+-` |
| Reset font size | `Alt+0` |

## Mouse

| Action | Mouse gesture |
| --- | --- |
| Copy the selection to the clipboard | Right-click |
| Open a horizontal split in the current directory | Middle-click |
| Close the current window | `Shift` + middle-click |

## Notes

- `Ctrl+Shift+Left`, `Ctrl+Shift+Right`, `Ctrl+Shift+Up`, and
  `Ctrl+Shift+Down` are mapped to `no_op` in Kitty, disabling Kitty's own
  actions for those combinations.
- Split orientation follows Kitty's `hsplit` and `vsplit` locations.
