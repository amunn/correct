# Corrections script

This script takes an input file and a comma separated list of corrections which
it applies to the file, producing a separate output file for safety.

## Usage

    correct -i <input file> -c <corrections file>
    correct -h


## Input file

The input file is any text file (typically your .tex source)

## Corrections file

The corrections file contains pairs of words or regular expressions separated
by a comma. The first element is the search regex and the second is the replace regex.

Since global regex replacement can be quite tricky, it's best to test carefully!
