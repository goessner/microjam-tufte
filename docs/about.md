---
"layout": "page",
"title": "About"
---

# About this Style 

## Edward Tufte

There are a lot informative publications and articles about the work of [Edward Tufte](https://en.wikipedia.org/wiki/Edward_Tufte), an American statistician and professor emeritus of political science, statistics, and computer science at Yale University.

## The Web Related Work of Edward Tufte

There are a few Edward Tufte [GitHub projects](https://github.com/edwardtufte) and among these we find [Tufte CSS](https://edwardtufte.github.io/tufte-css/). 

> Tufte CSS provides tools to style web articles using the ideas demonstrated by Edward Tufte’s books and handouts. Tufte’s style is known for its simplicity, extensive use of sidenotes, tight integration of graphics with text, and carefully chosen typography.    
>-- *Dave Liepmann*

Adoption of `'tufte.css'` to &mu;Jam was quite easily accomplished thanks to the high quality and readability of the stylesheet &ndash; credits go to [Dave Liepmann](https://www.daveliepmann.com/). It was not possible to realize all features of the *Tufte Style* in the Markdown context due to syntax and time restrictions. 

Especially those remarkable sidenotes and margin notes are missing. Maybe someone would like to help out here.

You will find the original `tufte.css` in the `/docs/theme/` folder, which is only for comparison and might be deleted without harm. In subdirectory `/docs/theme/et-book/` the font files are located, which are responsible for the noteworthy typography. As with all other &mu;Jam themes `styles.css` is the stylesheet for the [resulting webpages](https://goessner.github.io/microjam-tufte/) and contains the subset of *Tufte Style* used. But in contrast to other &mu;Jam themes we have another stylesheet `preview.css` in that folder, which injects  the *Tufte Style* even into VSCode's native markdown preview.

*microJam - Tufte Style* is primarily intended for scientific publications and articles. This is the reason, why *math* is enabled her. But &ndash; of course &ndash; this template might be used by all others who like it.
