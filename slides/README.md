To build the slides:

```
pandoc \
    --section-divs \
    -t revealjs \
    -s \
    --metadata title="Understanding the structure of cities through the lens of data" \
    --variable theme="ugai" \
    --template template.revealjs \
    -o intro.html \
    intro.md
```
