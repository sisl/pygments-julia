# pygments-julia6

A custom Julia 0.6 lexer for [Pygments](http://pygments.org/).

## Install

    $ git clone https://github.com/sisl/pygments-julia6
    $ cd pygments-julia6
    $ (sudo) python setup.py install

## Verify

Verify that the package installed correctly by looking for the lexers "julia6" and "jlcon6" in the output of

    $ pygmentize -L lexers
