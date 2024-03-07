# Daylight Colorscheme for Neovim (WIP)

Daylight is a vibrant, outdoor-friendly colorscheme for Neovim that thrives under the bright sunlight. It is built using [Lush.nvim](https://github.com/rktjmp/lush.nvim) framework to provide a pure white background that minimizes screen reflections and utilizes a palette designed for optimal legibility in sunlight.

## Features

- **Pure White Background**: Maximizes readability outdoors by reducing glare and reflections.
- **Eye-friendly Colors**: Carefully selected colors to ensure text is easily distinguishable without straining the eyes.
- **Outdoor Optimization**: Avoids the use of bright yellow and green on important elements to maintain visibility on a white background.
- **Work In Progress**: The color selection my change radically from what it is now, but the goal remains to create a colorscheme that is useful when working outdoors on a laptop screen.

## Installation

Daylight can be installed using various package managers. Below are instructions for some common setups.

### Prerequisite

Ensure `termguicolors` is enabled:

```vim
vim.opt.termguicolors = true
```

#### lazy.nvim
```
require("lazy").setup({
    {
        'michelrandahl/daylight',
        dependencies = { "rktjmp/lush.nvim" },
    },
})
```
