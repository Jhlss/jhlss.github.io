<!--
Add here global page variables to use throughout your website.
-->
+++
author = "João Henrique Lírio da Silva"
mintoclevel = 2

# Base URL of the website (GitHub Pages user site, no subpath needed).
# please do read the docs on deployment to avoid common issues: https://franklinjl.org/workflow/deploy/#deploying_your_website
# prepath = ""

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS is off: it only includes pages that define `@def rss = "..."`, and this
# site has no blog/news pages yet. Set to true and add `rss` to a page's
# front matter to start publishing a feed.
generate_rss = false
website_title = "João Henrique Lírio da Silva"
website_descr = "PhD in Mathematics (UFRJ) — researcher in ergodic theory, chaotic dynamical systems and rigorous computational approaches."
website_url   = "https://jhlss.github.io/"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
