# pygments-julia6

A custom Julia 0.6 lexer for [Pygments](http://pygments.org/).

## Install

    $ git clone https://github.com/sisl/pygments-julia6
    $ cd pygments-julia6
    $ (sudo) python setup.py install

## Verify

Verify that the package installed correctly by looking for the lexers "julia6" and "jlcon6" in the output of

    $ pygmentize -L lexers

## Acknowledgments

This package is based to some extent on the pull request [here](https://bitbucket.org/natashawatkins/pygments-main/src/a893dbff5bfc4359d07d222bb9c3b4a0dec062bc/pygments/lexers/julia.py?fileviewer=file-view-default) and the regular expressions for Sublime highlighting [here](https://github.com/JuliaEditorSupport/Julia-sublime/blob/master/Julia.sublime-syntax). Contributions came from Sidd Rao, Tim Wheeler, and Mykel Kochenderfer.