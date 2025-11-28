# 0x03. Shell, init files, variables and expansions

This project is about practicing shell initialization files, variables, expansions, arithmetic, and aliases in Bash on Ubuntu 20.04 LTS.

All scripts:

- Are exactly 2 lines long (`#!/bin/bash` plus one command).
- Are executable.
- Do not use `&&`, `||`, `;`, `bc`, `sed`, or `awk`.

## Files

- **0-alias**  
  Creates an alias named `ls` that runs a command that removes all files in the current working directory.

- **1-hello_you**  
  Prints `hello <user>`, where `<user>` is the current Linux user.

- **2-path**  
  Adds `/action` to the end of the `PATH` environment variable.

- **3-paths**  
  Prints the number of directories in the `PATH` variable.

- **4-global_variables**  
  Lists all environment variables.

- **5-local_variables**  
  Lists all local variables, environment variables, and shell functions.

- **6-create_local_variable**  
  Creates a local shell variable `BEST` with the value `School`.

- **7-create_global_variable**  
  Creates a global (environment) variable `BEST` with the value `School`.

- **8-true_knowledge**  
  Prints the result of `128` plus the value stored in the `TRUEKNOWLEDGE` environment variable, followed by a new line.

- **9-divide_and_rule**  
  Prints the result of dividing the environment variable `POWER` by the environment variable `DIVIDE`, followed by a new line.

- **10-love_exponent_breath**  
  Prints the result of raising the environment variable `BREATH` to the power of the environment variable `LOVE`, followed by a new line.

- **11-binary_to_decimal**  
  Converts the binary number stored in the `BINARY` environment variable to base 10 and prints the decimal value.

- **12-combinations**  
  Prints all possible combinations of two lowercase letters from `a` to `z`, one combination per line, in alphabetical order. The combination `oo` must not be printed.

- **13-print_float**  
  Prints the value of the environment variable `NUM` as a floating-point number with two decimal places, followed by a new line.

