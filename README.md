# Thesis Template UOS

This is a thesis template I used for my Bachelor's thesis. It is roughly based on the [template
provided by the Knowledge Based Systems Group](http://www2.inf.uos.de/kbs/thesis_KBS.zip) of the Osnabrück University.
Note that this is no official template!


# Compilation notes

To compile it, you should run the following commands:

```
pdflatex Thesis.tex
bibtex Thesis.aux
pdflatex Thesis.tex
pdflatex Thesis.tex
```

Yes, run `pdflatex` three times. You might even need a fourth time if dealing with indices and
glossaries.

You can place all images in an `img` directory and just reference them by their names. E.g. if
`myImage.png` was in it (`img/myImage.png`) you would include it just with the name:

```
\includegraphics{myImage.png}
```

There are several different options provided, see the comments in the file `Thesis.tex` until
I find the time to describe them here in more detail.


# Important matters

Note that this thesis template contains lots of stuff important for the Osnabrück University:
The declaration of authorship is taken from the Cognitive Science program (see
[here](http://ikw.uni-osnabrueck.de/en/cogsci/examination_bachelor#bachelor_thesis_registration)).
Also the logo is taken from the Osnabrück University (if I remember correctly from
[the original template's zip](http://www2.inf.uos.de/kbs/thesis_KBS.zip)).

If you want to change those things to make this template feasible for your thesis, take a look at
the `base` directory. You might want to replace the `unilogo.eps` and also change its reference in
the `thesis.cls`. In case you have a problem, feel free to drop me a line.


# Contribute

To contribute to this, please fork the repository and create a pull request. I will get in touch.
