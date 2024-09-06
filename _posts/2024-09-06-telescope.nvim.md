---
layout: post
title: "Telescope.nvim"
category: Development Environment
---

```
Plug 'nvim-lua/plenary.nvim'    " For nvim-telescope
Plug 'nvim-telescope/telescope.nvim', { 'tag': '0.1.8' }
Plug 'nvim-treesitter/nvim-treesitter', {'do': ':TSUpdate'} " For nvim-telescope
```

```
" telescope.nvim
nnoremap <leader>ff <cmd>Telescope find_files<cr>
nnoremap <leader>fg <cmd>Telescope live_grep<cr>
nnoremap <leader>fb <cmd>Telescope buffers<cr>
nnoremap <leader>fh <cmd>Telescope help_tags<cr>
```

need install `rg`, `fd`
