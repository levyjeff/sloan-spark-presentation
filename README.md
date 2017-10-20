# sloan-spark-presentation

## To build slidehow:

Pandoc must be installed (not a default conda package), then replace the path with your local path.

jupyter nbconvert --to slides "index.ipynb" --SlidesExporter.reveal_transition=convex --reveal-prefix reveal.js --ServerPostProcessor.ip="0.0.0.0" --ServePostProcessor.port=8910 --post serve