

# introduction #
This wiki page gives some informations on the nsp help which is still not completed. Its purpose
is also to have some feed-back from users which can post comments at the end of this wiki page.

The nsp help is organized as a collection of chapters, each one being a list of
functions/methods/topics. See [a snapshot of the current help pages](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manual.html). Here, for each chapter,  we list some functions not already documented and also some missed chapters together
with a list of functions they should contain (waiting for a complete set of chapters we have put some already documented
help pages in a misc chapter).

# a few remarks about the organization #
  * an help page could be referenced by several chapters (for instance the umfpack page is referenced both by the data type and the linear algebra chapters).
  * the "summary page" of each chapter should be written by hand and this lets an additionnal freedom to organize the chapter presentation.
  * a page (which is a latex file) can contain the description of several functions (examples: min, max, minmax functions, sum and prod functions, complex, real, imag functions).

# users feedback #

If you want to suggest some improvments don't hesitate to write a comment at this end of this page (you just need a [google account](https://accounts.google.com)). For instance :
  1. if you need the help page of a function which is still not documented (btw you can suggest one or two (or more) chapter from which it can be referenced).
  1. you can suggest improvments:
  * in the general organization
  * in the organization of a given chapter
  * in a given help page which is not clear, which lacks some examples, etc...

# existent chapters #

## data\_types ##

> [current data\_types chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli1.html)

> Some missed pages:
    1. GdkPixbuf - nsp image type (this is nevertheless documented in the ImagesInNsp wikipage)

## basic arrays functions ##

> [current basic arrays functions chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli20.html)

> Some missed pages:
    1. ndind2ind
    1. is, type - query object type -

## basic functions or methods for numerical matrices ##

> [current basic functions or methods for numerical matrices chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli33.html)

> Some missed pages:
    1. real and complex numbers, floating point number (link to floating point and integer numbers properties)
    1. empty matrices rules
    1. : operator
    1. usual operators +, -, **, /, .**, ./, <sup>, .</sup>
    1. add (a short description is available in the Mat data type help page)
    1. spones (the description is available in the SpColMat data type)
    1. speye (the description is available in the SpColMat data type)
    1. full (the description is available in the SpColMat data type)
    1. sparse (the description is available in the SpColMat data type)
    1. nnz (the description is available in the SpColMat data type)

## strings ##

> [current strings chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli51.html)

> No missed pages ?

## numbers (properties, display,...) ##

> [current numbers chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli69.html)

> Some missed pages:
    1. intmin, intmax - min and max for integer types (IMat)
    1. clean

## miscellaneous ##

> [current misc chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli83.html)

> help pages from this chapter will be dispatched in future new chapters

## numerics (ode, f(x)=0, integrals, interpolation, optimization,...) ##

> [current numerics chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli96.html)

> Possibly this chapter will be split in the future...

> Some missed pages:
    1. optim

## signal processing ##

> [current signal processing chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli112.html)

> Some missed pages:
    1. fft2, ifft2

## searching and sorting (find, search, sort, set functions...) ##

> [current searching and sorting chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli116.html)

> No missed pages ?

## linear algebra ##

> [current linear algebra chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli128.html)

> Some missed pages:
    1. the backslash operator
    1. det
    1. gspec
    1. solve\_banded
    1. lsq
    1. hess
    1. balanc

## random numbers generation, statistics functions, density and cdf functions ##

> [current chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli150.html)

> Some missed pages:
    1. rand\_discrete - random number generation for given user finite discrete distributions
    1. sprand - uniform or normal random numbers in sparse matrix
    1. kcdf, kcdflim - kolmogorov and limit kolmogorov cdf functions

## Gui ##

> [current chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli175.html)

> Currently only old scilab gui functions are described may be we have to put here all
> gtk stuff which is available from nsp.

## Graphics ##

> [current chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli184.html)

> Most functions are not documented.


## Files, I/O, system functions ##

> [current chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli188.html)

> Some missed pages:
    1. system - send command to operating system
    1. spawn -
    1. spawn\_sync -
    1. spawn\_async -

## Play and record sound samples ##

> [current chapter](http://www.iecn.u-nancy.fr/~pincon/nsp/nsp_manual/manualli207.html)

> No missed pages ?


# non existent chapters #

## programming ##

> It should expose the main nsp language structures...
    1. function, endfunction - keywords delimiting a function definition
    1. is, type - query object type
    1. for and while loops, break - loop constructs
    1. if, select - tests
    1. try catch
    1. ....

## elementary and special math func ##

  * elementary
    1. modulo, mod
    1. floor, ceil, round, clean

  * elementary transcendental
    1. sqrt
    1. hypot
    1. exp, log, lop1p
    1. sin, asin, sinpi, cos, acos, tan, atan
    1. sinpi, cospi, tanpi, cotanpi
    1. sinh, asinh, cosh, acosh, tanh, atanh

  * special math func
    1. gamma, gammaln, digamma
    1. erf, erfc, erfcx
    1. bessel
    1. ....



# latex help related explanations #

The nsp help is build from latex pages. It is converted in html using
Eitan Gurary [ht4latex](http://www.cse.ohio-state.edu/~gurari/TeX4ht/mn.html) code.

This section _needs certainly supplementary explanations_

## tricks ##

The file `nsp2/man/src/model/model.tex` gives several tricks. In particular there are different ways to introduce nsp code but we recommend to use the `Verbatim` (note the upper case V) which is much much simpler than using \begin{program} \HCode, etc...):

```
\begin{Verbatim}
my lines of nsp code just as if it
is in its own text file
\end{Verbatim}
```


## the summary chapter file ##

These source files are located in `nsp2/man/src/`. Once you have wrote an help page (to place in a `nsp2/man/src/chapter_name` directory) you should add two entries (an hyperlink and an input command) inside its corresponding summary chapter file (generally `nsp2/man/src/chapter_name.tex`). See one of these files.

## compilation ##

Different solutions:
  * in `nsp2/man/html/generated`, enter `make manual`. All the manual is compiled (this is time consuming); latex errors are displayed and the system wait for an answer (as usual you can enter x to continue). Note that the index is not updated.
  * in  `nsp2/man/html`, enter `make manual`. Use only this way when you are sure that the whole help compiles (otherwise latex errors freeze the compilation). The index is updated.
  * Jpc says: on obtient le man d'un example particulier en tapant `make` dans `nsp2/man/html-one` ou `make
> MANPAGE=model/model.tex` (par defaut on obtient le man de model).