# clw1999
LaTeX TikZ re-creation of the diagram ""Organizational learning as a Dynamic Process" from Crossan,Lane &amp; White 1999 AMR:24:3:522-537 (Figure 1, p532).

This re-creates in LaTeX and TikZ, Figure 1 on page 532 from this paper:
```
An Organizational Learning Framework: From Intuition to Institution
Mary M. Crossan, Henry W. Lane and Roderick E. White
The Academy of Management Review
Vol. 24, No. 3 (Jul., 1999) , pp. 522-537
Published by: Academy of Management
```
Stable URL: (http://www.jstor.org/stable/259140)[http://www.jstor.org/stable/259140]

## Referencing
If you use this diagram, you should reference it directly, as "Newton,G. 2015, after Crossan, et al. 1999".

#Original Diagram
This is the original diagram.
Note this diagram is copyright(c) Academy of Management.
![Original image. Copyrighted image](https://raw.githubusercontent.com/gnewton/clw1999/master/ORIGINAL_Crossan_Lane_White_AMR24_3_1999_figure1_p532.jpg)

#Requirements
Needs install of LaTeX and TikZ.
Needs TikZ packages: 
* `arrows`
* `decorations.markings`
* `positioning`
* `shapes.geometric`

#Building
##PDF
```
$ pdflatex Crossan_Lane_White_AMR24_3_1999_figure1_p532.tex
```

## JPEG
```
$ gs -dSAFER -dBATCH -dNOPAUSE -sDEVICE=jpeg -dDOINTERPOLATE -dTextAlphaBits=4 -dGraphicsAlphaBits=4 -r600x600 -dMaxBitmap=500000000 -dAlignToPixels=0 -dGridFitTT=2 -sOutputFile=Crossan_Lane_White_AMR24_3_1999_figure1_p532.jpg Crossan_Lane_White_AMR24_3_1999_figure1_p532.pdf
```

# Sample JPEG output


![alt text](https://raw.githubusercontent.com/gnewton/clw1999/master/Crossan_Lane_White_AMR24_3_1999_figure1_p532.jpg)


#Licence
![CC logo](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

Licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/)

