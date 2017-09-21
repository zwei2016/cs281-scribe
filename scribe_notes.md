### How to write scribe notes

So that we don't have to go back and correct your scribe notes for style, follow the following rules:

1. Do not end lines with the `\\` command. Instead, do not delineate between two different lines of the same paragraph, and insert a blank line between consecutive paragraphs. Ideally, you can insert a `\smallskip` between paragraphs, but it's ok not to (just be consistent). 
2. Use the `\begin{align*}` environment when you wish to write equations that you *do not* want to refer to later. Don't use the `align*` environments for equations with 1 line, use `$$` instead. It's ok to use `\[\]`
3. Use `\on` (short for `\operatorname`) for text that refers to symbols, like `\on{Bern}` or `\on{trace}`. 
4. Don't indent your text for `\subsection`, etc. Indent for `\begin{itemize}` or `\begin{enumerate}` environments.
5. Always use `\sin` instead of `sin`, and similarly for other functions (log, cos, etc.). We've defined a `\exp`, though it's not standard.