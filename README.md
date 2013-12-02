### ::usage messages on stackexchange

[Direct link to userscript](http://simonschmidt.github.io/SE-Usage-Message/m_usage.user.js)

Put a tooltip with ::usage on builtin symbols in code blocks.

The ::usage is converted to unicode, where possible sub and supscript symbols are used
otherwise it's displayed like Subscript[a, b].

Uses the fact that prettify with lang-mma.js puts builtin symbols in a span with class 'kwd', 
so code inside codeblocks works fine, as does inline code with just one symbol name like `Symbol`

![Pause tooltip](http://simonschmidt.github.io/SE-Usage-Message/img/examplePause.png)
