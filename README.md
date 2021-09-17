# booklet-first-album
## Latex source for our first album booklet

- Compile with xelatex: **xelatex main.tex**
- Resize jpg: **convert -strip -interlace Plane -gaussian-blur 0.05 -quality 75% image.jpg image_small.jpg**
- *verse* package helps structure the lyrics
- *mhchem* package is for chemical formulas
- *graphicx* package is for adding graphics
- *eso-pic* package is used to add background pictures
- *hyperref* package is for hyperlinks
- *geometry* package is for page layout
- *Noto Sans CJK* font is used for Chinese Japanese Korean characters, with *ctex* package
- Korean spaces have to be forced
- Paragraph breaks are forced with  \ \
