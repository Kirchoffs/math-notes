# LaTeX Notes

## LaTeX Packages
```
\usepackage{package-name}
```

### Lipsum
This package gives you easy access to 150 paragraphs of the Lorem Ipsum dummy text provided by https://lipsum.com, plus a growing list of other dummy texts in different languages.
```
\usepackage{lipsum}

\lipsum
\lipsum[1-1]
```

## Math Related Symbols
```
xor: \oplus
round down: \lfloor{x}\rfloor
```

## Layout
### Line spacing
```
\linespread{1}
```

### Add extra empty line
```
Hi there \bigskip
```
Also, we have `\medskip` and `\smallskip`.

### Just new line
```
Hi there \par
```

```
Hi there \\
```

In general, it's best to use \\ within appropriate environments like tabular or align, and use blank lines or \par to create new paragraphs in regular text. This ensures proper formatting and prevents unexpected issues.
