# work-hats-book
Public Repository of the Opensource book "Work Hats"

## How to build the ebook

`mkdir -p dist && pandoc --toc --epub-embed-font='fonts/*.ttf' -o dist/work-hats-book.epub metadata.txt 00-preface/*.md 01-contents/*.md 02-conclusions/*.md`

**mobi**
`kindlegen dist/work-hats-book.epub  -o work-hats-book.mobi`


## License & Copyright

The materials herein are all &copy; 2019 Andrea Grassi
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivs 4.0 Unported License</a>.