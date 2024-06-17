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

# Notes

I use the environment variable VIRTUAL\_ENV to store the penv, the same as the Python venv. That way
one can just display that variable in ones prompt and have it work for Python and Perl. Hence
I also removed the prompt modification that was in the original script, as I already display VIRTUAL\_ENV
in my prompt if it is set.
