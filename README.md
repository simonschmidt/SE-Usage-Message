### ::usage messages on stackexchange

Put a tooltip with ::usage on builtin symobls in code blocks.

The ::usage is converted to unicode, where possible sub and supscript symbols are used
when that's not possible it's displayed like Subscript[a, b].

Uses the fact that prettify with lang-mma.js puts builtin symbols in a span with class 'kwd', 
so code inside codeblocks works fine, as does inline code with just a symbol name like `Symbol`



