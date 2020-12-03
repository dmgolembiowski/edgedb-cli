#### Issue 14: Vim mode:

- [ ] Vi-like (visual//visual-block) mode

- [ ] Prevent accidental closures of the CLI via <kbd>Ctrl</kbd>+<kbd>d</kbd>.

> ```rust
> // Prevent accidental session quitting with CTRL-D
> if (OS == Linux || Unix) { match input("Close the session? [ Y | N ]: ") { ... }
> // Windows users will be accustomed to using CTRL-C for "CUT / YANK"
> else { ...ToDoItem }
> ```

- [ ] Skip whitespace-separated "words": <kbd>Alt</kbd>+<kbd>↔</kbd>

- [ ] Tab indentation (insert 4 whitespace characters on the current line): <kbd>Tab</kdb>
