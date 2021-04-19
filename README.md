# Corrections script

This script takes an input file and a comma separated list of corrections which
it applies to the file, producing a separate output file for safety.

## Usage

    correct -i <input file> -c <corrections file>

    correct -h
    
Example with the supplied test files:

    correct -i corr_test.tex -c corrections.txt


## Input file

The input file is any text file (typically your .tex source)  A sample input file
is given in `corr_test.tex`.

## Corrections file

The corrections file contains pairs of words or regular expressions separated
by a comma. The first element is the search regex and the second is the replace regex.

A sample corrections file is given in `corrections.txt`.

Since global regex replacement can be quite tricky, it's best to test carefully!
