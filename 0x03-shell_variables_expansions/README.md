# 0x03. Shell, init files, variables and expansions

## 📂 Directory: `0x03-shell_variables_expansions`

This directory is part of the **ALX System Engineering & DevOps** project. It focuses on **Shell variables, initialization files, and expansions**.

---

## ✅ Learning Objectives

By the end of this project, you should be able to explain:

- What happens when you **type `$ ls -l *.txt`**
- What are **expansions** and the different types (brace, parameter, command substitution, arithmetic, etc.)
- What **shell variables** are and the difference between **local and global variables**
- What **special parameters** are and how to use them
- The purpose of **init files** like `.bashrc` and `.profile`
- How to **perform arithmetic operations** in the shell
- How to **create, update, and delete shell variables**
- How to use the `alias` command

---

## 📌 Project Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- All scripts must be exactly **two lines long** (`$ wc -l file` should print 2)
- All scripts must **end with a new line**
- All files must start with `#!/bin/bash`
- You are not allowed to use `&&`, `||` or `;`
- You are not allowed to use `bc`, `sed` or `awk`
- All your scripts must be **executable**: `chmod u+x filename`

---

## 📜 Files and Descriptions

| File Name                  | Description                                                                       |
| -------------------------- | --------------------------------------------------------------------------------- |
| `0-alias`                  | Creates an alias `ls` with value `rm *`                                           |
| `1-hello_you`              | Prints `hello user`, where `user` is the current Linux user                       |
| `2-path`                   | Adds `/action` to the `PATH`                                                      |
| `3-paths`                  | Counts the number of directories in the `PATH`                                    |
| `4-global_variables`       | Lists environment variables                                                       |
| `5-local_variables`        | Lists all local variables and environment variables, and functions                |
| `6-create_local_variable`  | Creates a new local variable                                                      |
| `7-create_global_variable` | Creates a new global variable                                                     |
| `8-true_knowledge`         | Prints the result of the addition of 128 with the value stored in `TRUEKNOWLEDGE` |
| `9-divide_and_rule`        | Prints the result of `POWER` divided by `DIVIDE`                                  |
| `10-love_exponent_breath`  | Displays the result of `BREATH` to the power `LOVE`                               |
| `11-binary_to_decimal`     | Converts a number from base 2 to base 10                                          |
| `12-combinations`          | Prints all possible combinations of two letters, except `oo`                      |
| `13-print_float`           | Prints a number with two decimal places                                           |

---

## 🔑 Key Concepts Covered

- **Shell Initialization Files**: `.bashrc`, `.profile`, `.bash_profile`
- **Shell Variables**: `local`, `global` (`export`)
- **Expansions**:
  - **Brace Expansion**: `{a,b}`
  - **Parameter Expansion**: `$USER`, `${VAR}`
  - **Arithmetic Expansion**: `$(( expression ))`
  - **Command Substitution**: `$(command)`
- **Aliases**: `alias name='command'`

---

## ▶️ How to Run the Scripts

Clone the repository and navigate to the directory:

```bash
git clone https://github.com/your-username/alx-system_engineering-devops.git
cd alx-system_engineering-devops/0x03-shell_variables_expansions
```
