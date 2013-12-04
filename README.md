### ::usage messages on Mathematica symbols

[Direct link to userscript](http://simonschmidt.github.io/SE-Usage-Message/m_usage.user.js)

Put a tooltip with ::usage on builtin symbols on [mathematica.stackexchange.com](http://mathematica.stackexchange.com)
and [Wolfram Community](http://community.wolfram.com/)


![Pause tooltip](http://simonschmidt.github.io/SE-Usage-Message/img/examplePause.png)


The script does no attempt to parse code but relies on the fact that
both mma.SE (Thanks to halirutans work on lang-mma.js) and WC tag builtin
symbols with a special class, making them easy to detect.

### Limitations

* Sub and supescripts are only partially supported by unicode, so some
  descriptions have the full-form "Subscript" and "Subsuperscript"
  (Same goes for under and overscript that is completely missing)

* Mathematica uses a lot of symbols in the unicode PUA I've mapped
  the ones I could find similar looking characters for, others are
  left as-is (See Conjugate for instance)

* The ::usage was taken from v8 so any newer symbols are not included
