# 0x03. Shell, init files, variables and expansions

---

## Project Structure

| File | Description |
|------|-------------|
| `0-alias` | Creates an alias `ls` that runs `rm *` |
| `1-hello_you` | Create a script that prints hello user, where user is the current Linux user |
| `2-path` | Add `/action` to the `PATH` and `/action` should be the last directory the shell looks |
| `3-paths` | Create a script that counts the number of directories in the PATH |
| `4-global_variables` | Create a script that lists environment variables |
| `5-local_variables` | A script that lists all local variables and environment variables, and functions |
| `6-create_local_variable` | Create a script that creates a new local variable |
| `7-create_global_variable` | Create a script that creates a new global variable |
| `8-true_knowledge` | Prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE` |
| `9-divide_and_rule` | Prints the result of `POWER` divided by `DIVIDE` |
| `10-love_exponent_breath` | A script that displays the result of BREATH to the power LOVE |

## Usage

To test script in the current shell environment, use `source`:

```bash
$ source ./file-name
```

Make script executable and run:

```bash
$ chmod +x file_name
$ ./file_name
```

## Requirements

* Ubuntu 20.04 LTS
* Bash shell
* Scripts should be executable and start with shebang `#!/bin/bash`

## License

This project is part of the ALX BE Software Engineering Program.



