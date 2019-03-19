# templates
Repository for poster/presentation/paper templates

## Poster (baposter)

The poster template is based on http://www.brian-amberg.de/uni/poster/. 

## Poster and Slides (Gemini/Metropolis with EPFL colors)

The poster_gemini template is based on beamerposter with the
[Gemini theme](https://www.anishathalye.com/2018/07/19/gemini-a-modern-beamerposter-theme/)
and an EPFL color scheme (based on the MIT color scheme of Gemini).
As the template requires the fonts **Raleway** and **Lato** (which must be installed separately),
LuaTeX is required for compilation.
(LuaTeX is also required for setting music with lyluatex.)

A similar theme can be used for beamer presentations by adapting the [metropolis](https://github.com/matze/mtheme) theme
``` tex
\documentclass{beamer}
\usepackage{metropolis}
\usepackage{metroepfl}
```
As with the poster theme, this requires LuaTeX (might work with XeTeX).
A dark theme can be enabled using `\metroset{background=dark}` after loading `metroepfl`.
For more options, refer to the [metropolis manual](http://mirrors.ctan.org/macros/latex/contrib/beamer-contrib/themes/metropolis/doc/metropolistheme.pdf).
