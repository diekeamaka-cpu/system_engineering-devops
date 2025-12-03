# 0x03-shell_variables_expansions

This repository contains Bash scripts for practicing shell variables, environment variables, aliases, and arithmetic operations.

## Scripts

- Creates an alias `ls` with the value `rm *`.  
  Example: after sourcing the script, executing `ls` will remove all files in the current directory.

- Prints `hello user`, where `user` is the current Linux user.

- Adds `/action` to the `PATH` environment variable, ensuring it is appended as the last directory in the search path.

- Counts the number of directories listed in the `PATH` and prints the total.

- Lists all environment variables currently set in the shell session.

- Lists all local variables, environment variables, and shell functions.

- Creates a new local variable:  
  - Name: `BEST`  
  - Value: `School`

- Creates a new global variable:  
  - Name: `BEST`  
  - Value: `School`

- Prints the result of adding `128` to the value stored in the environment variable `TRUEKNOWLEDGE`.

- Prints the result of dividing the environment variable `POWER` by `DIVIDE`.

- Prints the result of `BREATH` raised to the power of `LOVE`.

- Makes scripts executable with `chmod +x <script>` and executes them using `./<script>`.
