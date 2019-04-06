<img src="https://cdn-images-1.medium.com/max/1200/1*JbJ98XkVFGBsFyfk-1lE9g.png" width="200" />

# Vim Tutor Cheatsheat
Cheatsheet for [Vim Tutor](http://www2.geog.ucl.ac.uk/~plewis/teaching/unix/vimtutor).

Vim Tutor comes installed with most modern MacOS and Linux distributions. To run it, enter `vimtutor` in the terminal.
For Windows there should be an entry in the start menu folder titled "vim tutor" if you install Vim.

## Lesson 1
1. The cursor is moved using either the arrow keys or the `h j k l` keys.
   - `h` : left
   - `j` : down
   - `k` : up
   - `l` : right
2. To start Vim from the shell prompt type: `vim FILENAME <ENTER>`
3. To exit Vim, type:
   - `<ESC> :q! <ENTER>` to trash all changes
   - `<ESC> :wq <ENTER>` to save the changes
4. To delete the character at the cursor, type: `x`
5. To insert or append text, type:
   - `i` type inserted text `<ESC>` (insert before the cursor)
   - `A` type appended text `<ESC>` (append after the line)
   
Note: Pressing `<ESC>` will place you in `NORMAL` mode or will cancel an unwanted and partially completed command.
