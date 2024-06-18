# penv
Penv is to perl what venv is to python. Somewhat. :P

# Synopsis

    penv .penv
    . .penv/bin/activate

# Installation

copy the file penv to somewhere on your path

# Usage

    penv <directory>

Creates a new penv.

    . <directory>/bin/activate

Activates the new penv

    cpanm <args>
    carbon <args>

Use localized cpanm and carbon instances

# Environment

The variable `LOCAL\_ENV` is set to the new virtual perl environment, like the Python `VIRTUAL\_ENV` variable.
This variable can be used to modify your prompt. Code to do so automatically is left commented out in the activate script.
