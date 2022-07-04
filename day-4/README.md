# Day-4

## Target

- Know Git commit and Git stage area.
- Know what is CSS and how to apply CSS.
- (Low priority) Know some basic CSS attributes.

## Resources

- (**MAIN**) Video [9.x CSS in a day](https://biaoyansu.com/9.x)
- E-book [Pro Git](https://bingohuang.gitbooks.io/progit2/content/)
- Web [CSS: Cascading Style Sheets](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Tasks

- [ ] Make your [vuejs.org](vuejs.org) copy more beautiful by apply some CSS.
- [ ] Use Git Conventional Commit to save your code.

## Guide

### Git

In general, git conventional commits looks like:

```text
<type>[scope]: <message>

e.g.

feat: xxx
fix: xxx
chore: xxx
```

- `type`: your commit type, a feature or a bugfix or something else.
- `scope`: which part of the code has been changed, optional.
- `message`: just a message to describe the changes.

If you don't know which `type` to use, use `chore` for now.

### CSS

some code references:

```css
/** element selector */
body {
  padding: 0;
  margin: 0
}
button {
  background-color: gray;
  border-radius: 3px;
  border: 1px solid green;
}
/** class selector */
.link {
  text-decoration: none;
}
/** id selector */
#app {
  font-family: sans-serif;
}
```

If you don't know what a specific CSS attribute do, ask [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS).

For example, you can find what `background` mean [here](https://developer.mozilla.org/en-US/docs/Web/CSS/background).
