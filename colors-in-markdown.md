# Testing colors in markdown

adding a bit of plain text (trying to deconfuse the renderer)

```diff
@@ purple @@
```

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

https://stackoverflow.com/questions/11509830/how-to-add-color-to-githubs-readme-md-file

https://github.com/github/markup/issues/369

OK, works above, but, for some reason, the renderer gets confused below at the moment:

<h2>

```diff
  
- red
 
+ green

! orange

# gray

@@ purple @@

```

</h2>

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

and this

```diff
- red
+ green
! orange
# gray
@@ purple @@
```

```diff

- red

+ green

! orange

# gray

@@ purple @@

```

OK, so this coloring scheme just does not work within headers (like H2) anymore, but works otherwise...
