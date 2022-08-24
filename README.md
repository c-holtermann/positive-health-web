# positive-health-web

LaTeX / Tikz spiderweb for positive health

Adapted from https://texample.net/tikz/examples/spiderweb-diagram/

Create pdf:
``` bash
latex --output-format=pdf web_only.tex
```

Conversion to svg:
``` bash
inkscape --pdf-poppler "`pwd`/web_only.pdf" -o "`pwd`/web_only.svg"
```
(using inkscape 1.2.1 from snap on Ubuntu, text converted to curves)

Resulting image:

![Positive health web](https://github.com/c-holtermann/positive-health-web/blob/main/web_only.svg)

German:

![Positive health web german](https://github.com/c-holtermann/positive-health-web/blob/main/web_only_de.svg)
