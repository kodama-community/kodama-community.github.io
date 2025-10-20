
---
title: What motivated you to develop $\href{https://kodama-community.github.io/}{\includegraphics[height=0.7em, totalheight=0.7em, width=0.755em, alt=logo]{/assets/kodama.svg} ~ \color{fe7f7e}\text{Kodama}}$?
page-title: What motivated you to develop Kodama?
taxon: FAQ
---

$\gdef\latex{\href{https://www.latex-project.org/}{\color{#008080}\LaTeX}}$

$\gdef\katex{\href{https://katex.org/}{\color{#329894} \KaTeX}}$

$\gdef\forester{\href{https://www.forester-notes.org/index/index.xml}{\color{#00B770} \text{Forester}}}$

$\gdef\typst{\href{https://typst.app/}{\color{#239dad} \text{Typst}}}$

$\gdef\kodama{\href{https://kodama-community.github.io/}{\includegraphics[height=0.7em, totalheight=0.7em, width=0.755em, alt=logo]{/assets/kodama.svg} ~ \color{fe7f7e}\text{Kodama}}}$

The original motivation for the $\kodama$ project was to create a static blog engine that truly satisfied my needs, similar to what [Hexo][hexo], [Hugo][hugo], [Zola][zola] and [others](../ssg.md) do. 

- Unfortunately, for various reasons, these static site generators (SSGs) all have issues when it comes to mathematical writing, which severely limits expressive power. This frustration persisted until I discovered $\typst$ and $\typst$.
  
- I believe $\forester$ can meet the complex demands of mathematical writing, but if I wanted to migrate my old blog posts, I'd have to completely rewrite them. Another factor was LaTeX's slow compilation speed and suboptimal editing experience. So, I decided to replace $\forester$'s $\katex$ + $\latex$ scheme with $\katex$ + $\typst$.
  
- There's also a smaller, yet still important, reason: I wanted a fully automatic dark theme that just works [out-of-the-box][ootb].

[hugo]: https://gohugo.io/
[hexo]: https://hexo.io/
[zola]: https://www.getzola.org/
[ruby]: https://www.ruby-lang.org/
[ootb]: https://en.wikipedia.org/wiki/Out_of_the_box_(feature)
