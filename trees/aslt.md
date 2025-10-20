
---
title: Is there any software like that?
---

$\gdef\latex{\href{https://www.latex-project.org/}{\color{#008080}\LaTeX}}$

$\gdef\gerby{\href{https://gerby-project.github.io/}{\color{#c5000c} \text{Gerby}}}$

$\gdef\katex{\href{https://katex.org/}{\color{#329894} \KaTeX}}$

$\gdef\obsidian{\href{https://obsidian.md/}{\color{#a78bfa} \text{Obsidian}}}$

$\gdef\forester{\href{https://www.forester-notes.org/index/index.xml}{\color{#00B770} \text{Forester}}}$

$\gdef\typst{\href{https://typst.app/}{\color{#239dad} \text{Typst}}}$

- $\obsidian$ looks great and has a rich ecosystem of community plugins, but I’d really prefer if it could:
  - Not break the rendering of normal $\katex$ formulas I write.
  - Support drawing non-rectangular commutative diagrams.
  - Provide theorem environments or something similar.
  - Be lightweight --- my disk space is running dangerously low from all the [Electron][electron]-based apps I've already installed.
  - Work well on mobile devices with the help of a terminal emulator like [Termux][termux].

- $\forester$ looks great, but ...
  - I'd prefer to write in [Markdown](https://commonmark.org/) and $\typst$.
  - I want an [out-of-the-box][ootb] dark theme, and vector graphics rendered by the application should also have their colors properly adjusted.
  - I'd like a table of contents that's always available, even on small-screen devices.

- $\gerby$ looks great, but ...
  - I don't intend to write in $\latex$.  
  - I can't fully accept [the tag system][tags].

[electron]: https://www.electronjs.org/
[ootb]: https://en.wikipedia.org/wiki/Out_of_the_box_(feature)
[tags]: https://stacks.math.columbia.edu/tags
[termux]: https://termux.dev/en/
