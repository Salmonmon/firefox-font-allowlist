# firefox-font-allowlist

An extended list of symbolic/icon fonts which should not be overridden by Firefox when forcing websites to use a custom font.

This is useful if you use modified fonts for text accessibility but want symbolic/icon fonts to show normally.
Firefox has a default font list for this, but it misses quite a few fonts, so this adds in others I have found.

## Setup
Go to about:config, find "browser.display.use_document_fonts.icon_font_allowlist" and copy the contents of "fontlist" to replace it's value.

I'm happy to add any fonts you find that I have missed if you send me the website in question

a quick note on mathjax: font overide may not play well with mathjax scaling such as on pmc.ncbi.nlm.nih.gov articles, I fixed this by overiding the font scaling manually with stylus for the mjx-math css object
