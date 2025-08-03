# Shell Variables and Expansions

This directory contains shell scripts that demonstrate various concepts related to shell variables, expansions, and shell scripting.

## Scripts Description

### 0-alias
Creates an alias named `ls` with the value `rm *`. This alias will delete all files in the current directory when `ls` is called.

### 1-hello_you
Prints "hello" followed by the current Linux user's username.

### 2-path
Adds `/action` to the PATH environment variable, making it the last directory the shell looks into when searching for programs.

### 3-paths
Counts and displays the number of directories in the PATH environment variable.

### 4-global_variables
Lists all environment variables (global variables) using the `printenv` command.

### 5-local_variables
Lists all local variables, environment variables, and functions using the `set` command.

### 6-create_local_variable
Creates a new local variable named `BEST` with the value `School`.

### 7-create_global_variable
Creates a new global variable named `BEST` with the value `School` using the `export` command.

### 8-true_knowledge
Prints the result of adding 128 to the value stored in the environment variable `TRUEKNOWLEDGE`.

### 9-divide_and_rule
Prints the result of dividing the value in environment variable `POWER` by the value in environment variable `DIVIDE`.

### 10-love_exponent_breath
Displays the result of raising the value in environment variable `BREATH` to the power of the value in environment variable `LOVE`.

### 11-binary_to_decimal
Converts a binary number stored in the environment variable `BINARY` to its decimal equivalent.

### 12-combinations
Prints all possible combinations of two lowercase letters (a-z), excluding "oo", in alphabetical order.

### 13-print_float
Prints a number stored in the environment variable `NUM` with exactly two decimal places.

### 100-decimal_to_hexadecimal
Converts a decimal number stored in the environment variable `DECIMAL` to its hexadecimal equivalent.

### 101-rot13
Encodes and decodes text using the ROT13 encryption algorithm.

### 102-odd
Prints every other line from the input, starting with the first line.

### 103-water_and_stir
Adds two numbers stored in environment variables `WATER` and `STIR` (in custom bases) and prints the result in base "bestchol".

## Requirements

- All scripts must be exactly 2 lines long (excluding the shebang)
- All files must end with a new line
- All files must be executable
- The first line of all files must be exactly `#!/bin/bash`
- No use of `&&`, `||`, `;`, `bc`, `sed`, or `awk` is allowed
