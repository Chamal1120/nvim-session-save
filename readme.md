## nvim session save config

This is a simple lua file to get vim session save feature to work on neovim with `init.lua`.

vim session saves (afaik),
1. Cursor position
2. Code folds
3. Buffers and their positions. (third party buffers have issues)

### How to setup

1. Clone the repo to your local directory.
2. Move the `session-save.lua` to the root of your neovim config (where init.lua file is located).
3. Import the `session-save.lua` file using the following command in your `init.lua` file.

```lua
require("session-save")
```

### To-do
[ ] Enable the neotree buffer save.

### Thanks 
