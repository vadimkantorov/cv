https://busytex.github.io/#https://github.com/vadimkantorov/cv

```
mkdir -p ./texmf/tex/latex

PACKAGE_URL=http://mirrors.ctan.org/macros/latex/contrib/titlesec.zip

wget -nc $PACKAGE_URL
unzip $(basename $PACKAGE_URL) -d ./texmf/tex/latex
```
