# sloan-spark-presentation

## To build slidehow:

Pandoc must be installed (not a default conda package), then replace the path with your local path.

jupyter nbconvert --to slides "c:\users\jeff\sloan presentation.ipynb" --SlidesExporter.reveal_transition=convex --post serve --reveal-prefix "http://cdnjs.cloudflare.com/ajax/libs/reveal.js/3.3.0"