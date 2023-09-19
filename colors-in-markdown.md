# Testing colors in markdown

adding a bit of plain text (trying to deconfuse the renderer)

```diff
@@ purple @@
```

```diff
- red
```

https://stackoverflow.com/questions/11509830/how-to-add-color-to-githubs-readme-md-file

https://github.com/github/markup/issues/369

<h2>

```diff
- red
+ green
! orange
# gray
@@ purple @@
```

the above used to work, but no more

how about

```diff
- red
```

```diff
+ green
```

```diff
! orange
```

```diff
# gray
```

```diff
@@ purple @@
```

Still no, although in README.md the purple one works. But today (Boston morning of Sep.19, 2023) everything is half-broken on GitHub,
contribution counter is not advancing, etc... Let's revisit later...
