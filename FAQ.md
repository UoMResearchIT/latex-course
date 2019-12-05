## How do I indent the first paragraph in a section?
The default behaviour in LaTeX is not to indent the first paragraph in a section. This follows publishing conventions --- just pick up a book at random and see that the first paragraph isn't indented, while subsequent paragraphs are.

However if you want to indent the first paragraph to match all the others, put this in your preamble:
```tex
\usepackage{indentfirst}
```

## In two-column mode, how can I make a figure span two columns?
Use the starred version of the figure environment
```latex
\begin{figure*} 
...
\end{figure*}
```
## Is there a UoM-styled beamer theme?
There is an unofficial theme [here](https://github.com/mundya/unofficial-university-of-manchester-beamer).


## How do I reference a page number?

Use the `\pageref` macro instead of `\ref`.  

```tex
\pageref{key}
```

The `\pageref{key}` command displays the page number of where `\label{key}` was used.