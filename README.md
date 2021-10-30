# sphinx
Building documents with sphinx

Open a terminal in the docs directory and run

    sphinx-quickstart
    Welcome to the Sphinx 3.4.3 quickstart utility.

    Please enter values for the following settings (just press Enter to
    accept a default value, if one is given in brackets).

    Selected root path: .

    You have two options for placing the build directory for Sphinx output.
    Either, you use a directory "_build" within the root path, or you separate
    "source" and "build" directories within the root path.
    > Separate source and build directories (y/n) [n]: y

    The project name will occur in several places in the built documentation.
    > Project name: sphinx
    > Author name(s): JT
    > Project release []: 

    If the documents are to be written in a language other than English,
    you can select a language here by its language code. Sphinx will then
    translate text that it generates into that language.

    For a list of supported codes, see
    https://www.sphinx-doc.org/en/master/usage/configuration.html#confval-language.
    > Project language [en]: 

    Creating file /home/john/github/sphinx/docs/source/conf.py.
    Creating file /home/john/github/sphinx/docs/source/index.rst.
    Creating file /home/john/github/sphinx/docs/Makefile.
    Creating file /home/john/github/sphinx/docs/make.bat.

    Finished: An initial directory structure has been created.

    You should now populate your master file /home/john/github/sphinx/docs/source/index.rst and create other documentation
    source files. Use the Makefile to build the docs, like so:
       make builder
    where "builder" is one of the supported builders, e.g. html, latex or linkcheck.

Open the docs/source/conf.py file and change the theme if you don't like the
default one.

[sphinx builtin themes]{https://www.sphinx-doc.org/en/master/usage/theming.html)
[third party themes](https://sphinx-themes.org)

