# positive-health-web

LaTeX / Tikz spiderweb for positive health

Adapted from https://texample.net/tikz/examples/spiderweb-diagram/

Create pdf:
``` bash
latex --output-format=pdf web_only.tex 
```

Conversion to svg:
``` bash
inkscape --without-gui --file=web_only.pdf --export-plain-svg=web_only.svg
```

Resulting image:

![Positive health web](https://github.com/c-holtermann/positive-health-web/blob/main/web_only.svg)
