# Lualine theme for Falcon colorscheme
Add lualine theme support for falcon colorscheme.

## Requirements
- [falcon.vim](https://github.com/fenetikm/falcon)

## Usage
```lua
require('lualine').setup({
  options = {
    theme = require('falcon-lualine').theme()
  }
})
```

## Notice
The `theme()` function does not ensure the `falcon` is installed. 
It will return an empty table when `falcon` does not exist.
