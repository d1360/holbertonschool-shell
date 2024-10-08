# Project: initfilesvariablesandexpansions

## Script 0-alias

This script creates an alias `ls` with the value `rm *`. When sourced, it replaces the `ls` command with a command that removes all files in the current directory.

# Project: init_files_variables_and_expansions

## Script 1-hello_you

This script prints `hello user`, where `user` is the current Linux user.

# Project: init_files_variables_and_expansions

## Script 2-path

This script adds `/action` to the `PATH` environment variable, making it the last directory the shell looks into when searching for a program.

# Project: init_files_variables_and_expansions

## Script 3-paths

This script counts the number of directories in the `PATH` environment variable.

# Project: init_files_variables_and_expansions

## Script 4-global_variables

This script lists all environment variables.

# Project: init_files_variables_and_expansions

## Script 5-local_variables

This script lists all local variables, environment variables, and functions.

# Project: init_files_variables_and_expansions

## Script 7-create_global_variable

This script creates a new global variable `BEST` with the value `School`.

# Project: init_files_variables_and_expansions

## Script 8-true_knowledge

This script prints the result of the addition of `128` with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line.

# Project: init_files_variables_and_expansions

## Script 9-divide_and_rule

This script prints the result of dividing the value stored in the environment variable `POWER` by the value stored in the environment variable `DIVIDE`, followed by a new line.


# Project: init_files_variables_and_expansions

## Script 10-love_exponent_breath

This script displays the result of raising the value stored in the environment variable `BREATH` to the power of the value stored in the environment variable `LOVE`, followed by a new line

# Project: init_files_variables_and_expansions

## Script 11-binary_to_decimal

This script converts a number from base 2 (binary) to base 10 (decimal). The binary number is stored in the environment variable `BINARY`, and the script displays the number in base 10, followed by a new line.


# Project: init_files_variables_and_expansions

## Script 12-combinations

This script prints all possible combinations of two lowercase letters (from 'a' to 'z'), except for "oo". Each combination is printed on a new line, and the output is alphabetically ordered starting with "aa". The script file contains a maximum of 64 characters.

# Project: init_files_variables_and_expansions

## Script 13-print_float

This script prints the number stored in the environment variable `NUM` with exactly two decimal places, followed by a new line. It uses the `printf` command to format the number correctly.

# Project: init_files_variables_and_expansions

## Script 14-decimal_to_hexadecimal

This script converts a decimal number stored in the environment variable `DECIMAL` to its hexadecimal representation. The result is displayed in base 16, followed by a new line.

# 15-rot13

This script encodes and decodes text using the ROT13 encryption method. ROT13 is a simple substitution cipher where each letter is replaced by the letter 13 positions after it in the alphabet. 

## Usage

To use this script, run it with an input file containing the text you want to encode or decode:

```bash
./15-rot13 < input_file

# 16-odd

This script prints every other line from the input, starting with the first line.

## Usage

To use this script, pipe the input into the script. For example, to list files and print every other line:

```bash
\ls -1 | ./16-odd

