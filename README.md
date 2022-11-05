# Skipta za optomehaniku na Hrvatskom jeziku
Pravim ovu skiptu jer mislim da će mi trebati. Ostali je mogu koristiti tako da ili skinu `*.PDF` datoteku ili sve `*.tex` datoteke i sami kompajliraju projekt.
Glavni file se zove `Optomechanics.tex`. Mogući način kompilacije je s naredbom 
```
pdflatex -synctex=1 -interaction=nonstopmode Optomechanics.tex  
bibtex reference
latex Optomechanics.tex
```

