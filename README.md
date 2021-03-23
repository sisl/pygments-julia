# Pygments Julia Lexer

A custom Julia lexer for [Pygments](http://pygments.org/).

## Install

You can use PIP:

    $ pip install --upgrade git+https://github.com/sisl/pygments-julia#egg=pygments_julia

Alternatively, you can run these commands

    $ git clone https://github.com/sisl/pygments-julia.git
    $ cd pygments-julia
    $ (sudo) python setup.py install

### Verify

Verify that the package installed correctly by looking for the lexers "julia1" and "jlcon1" in the output of

    $ pygmentize -L lexers

