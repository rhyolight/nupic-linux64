# nupic-linux64

Python distribution for NuPIC on linux.  This project provides a
fully-functional python environment in which to build and run
[NuPIC](https://github.com/numenta/nupic) in a 64-bit linux environment.

## Usage

Clone this repository:

    git clone https://github.com/numenta/nupic-linux64.git

Activate your environment:

    source nupic-linux64/bin/activate

Build NuPIC:

See https://github.com/numenta/nupic#configure-and-generate-build-files for
details.

To exit this environment when you are done:

    deactivate_nupic

## Building nupic requirements

A Makefile is provided should you need to reconstruct this environment.

    source bin/activate
    make
