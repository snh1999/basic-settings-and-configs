# vs_code_key_shortcut
My VS Code(ium) shortcuts


- `tab`/ `shift+tab` to browse through suggestions
- `ctrl+alt+v` to toggle vim mode ([vsCodevim](https://github.com/VSCodeVim/Vim))
- `alt+s` as `ctrl+left_arrow` substitue aka `cursorWordLeft`, in english move to `S`tart of previous word (works in all modes if [vsCodevim](https://github.com/VSCodeVim/Vim) is used)
  - `alt+shift+s` to select the word  
- `alt+e` as `ctrl+right_arrow` substitue (move to `E`nd of previous word aka `cursorWordEndRight`), add `shift` to select
- `alt+b` as `backspace`(character), `alt+shift+b` deletes the word
- `alt+j` moves line down `alt+k` moves line up (keeping similarity to normal mode j and k key)
- `alt+l` shows hovertext (similar to if we hover mouse over the key)

**Ones specific to ([vsCodevim](https://github.com/VSCodeVim/Vim))**
when in 
  - Normal mode:
    - `tab` and `shift+tab` lets us move around opened tabs(files)
  - Inset mode:
    - `ctrl+j` as `Esc` or move to normal mode and `ctrl+k` to move to visual mode directly (I couldn't get `alt` key to work for vim extension keybindings which wouldve made more sense -- for some reason <M/A-...> doesnt work)  
  - Visual mode
    - I have retained `ctrl+c` and `ctrl+v` for the task they have always been doing- copying and pasting (`vim.handlekeys` are disabled for a few keys)
    - `p`(paste) uses *clipboard copy text*
 
- `"vim.useSystemClipboard": true` ensures copy operation inside vim isn't specific to vim only, but for the whole system
- my vim <leader> is `space` key
