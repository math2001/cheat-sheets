## Tabs

- `gt` go to the next *tab*
- `gT` go to the previous *tab*

## Windows

### If `ctrl+w` isn't quite right

Every shortcut that will affect the windows starts with `ctrl+w` (w like
window). If it doesn't fit your need (on some terminal, ctrl+w closes the 
current tab), you can always remap it to an other one, and will affect *every*
shortcut starting by it:

    nnoremap <C-e> <C-w>

Now, `ctrl+e` will to the exact same as `ctrl+w` (so, you can now do `ctrl+e`,
`p` to go to the previous window)

### The shortcuts

#### Move the cursor across windows

- `ctrl+w`, `ctrl+w`: move the focus across the windows, in a clickwise
direction
- `ctrl+w`, `w` same as `ctrl+w`, `ctrl+w`
- `ctrl+w`, `p` goes to the Previous window
- `ctrl+w`, `T` move current window to a new *Tab*
- `ctrl+w`, `c` Close current window (if it was the last one, it'll close the
whole tab)

- `ctrl+w`, `j` gives the focus to the window below
- `ctrl+w`, `k` gives the focus to the window above
- `ctrl+w`, `h` gives the focus to the window on the left
- `ctrl+w`, `l` gives the focus to the window on the right


More info: `:help window-move-cursor`

#### Move the actual windows

And, what's just great about it is that if you use uppercased letters, instead
of moving the cursor, you'll move the *window*

- `ctrl+w`, `J` move the window bottom
- `ctrl+w`, `K` move the window top
- `ctrl+w`, `H` move the window to the very left
- `ctrl+w`, `l` move the window to the very right

More info: `:help window-moving`

#### Resize the windows

- `ctrl+w`, `>` increases the width
- `ctrl+w`, `>` decreases the width
- `ctrl+w`, `+` increases the height 
- `ctrl+w`, `+` decreases the height 
- `ctrl+w`, `=` set the windows' size to equal

More info: `:help window-resize`
