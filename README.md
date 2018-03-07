# Svg Spatial Sort


Reasonably efficient greedy path planning for plotting svg files.


## Install

Install locally using:

    ./setup.py install --user

## Use

Use it like this
    svgsort input.svg output.svg

Your best bet is probably

    svgsort input.svg output.svg --split --reverse

This will break down paths into continous sub paths. it will also allow
travelling along paths in both directions (but only once).

The default behaviour is to fit the result inside the dimensions of an A4 sheet
of paper. You can override this.

For other options, see:

    svgsort --help

