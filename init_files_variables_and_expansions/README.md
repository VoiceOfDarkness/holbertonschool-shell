# Shell Basics Cheat Sheet

This cheat sheet provides an overview of essential concepts related to shell scripting and working with the command line.

## General

- **$ ls -l *.txt**: List all files ending with ".txt" in the current directory in long format, showing detailed information about each file.

## Shell Initialization Files

- **/etc/profile**: System-wide shell initialization file, executed for all users during login.
- **/etc/profile.d**: Directory containing additional shell initialization scripts executed during system startup.
- **~/.bashrc**: User-specific shell initialization file for Bash, executed for each user during login.

## Variables

- **Local vs. Global Variable**:
  - Local variables are confined to a specific scope, such as a function.
  - Global variables are accessible from anywhere in the shell.

- **Reserved Variable**:
  - Reserved variables are predefined by the shell and have special meanings, e.g., HOME, PATH, PS1.

- **Creating, Updating, Deleting Variables**:
  - Create a variable: `variable_name=value`
  - Update a variable: `variable_name=new_value`
  - Delete a variable: `unset variable_name`

- **Reserved Variables**:
  - **HOME**: Represents the user's home directory.
  - **PATH**: Defines directories where the shell searches for executable files.
  - **PS1**: Sets the primary shell prompt.

- **Special Parameters**:
  - Special parameters have specific meanings in the shell.
  - **$?**: Contains the exit status of the last executed command.

## Expansions

- **Expansion**: Mechanism to manipulate and expand variables and commands in shell scripts.
- **Single vs. Double Quotes**:
  - Single quotes (''): Preserve the literal value of characters.
  - Double quotes (""): Allow variable and command substitution.

- **Command Substitution**:
  - `$()`: Enclose a command within `$()` to substitute its output.
  - Backticks (\`\`): Older syntax for command substitution (avoid using).

## Shell Arithmetic

- **Arithmetic Operations**:
  - Use `$((expression))` to perform arithmetic operations in the shell.
  - Example: `result=$((5 + 3))`

## The `alias` Command

- **Creating an Alias**:
  - Use `alias` command to create an alias for a longer command.
  - Example: `alias ll='ls -l'` creates an alias 'll' for 'ls -l'.

- **Listing Aliases**:
  - Use `alias` with no arguments to list all defined aliases.

- **Temporarily Disabling an Alias**:
  - To temporarily disable an alias, prefix the command with a backslash ('\').
  - Example: `\ll` will temporarily bypass the 'll' alias.

Remember to practice these concepts in a Unix-like shell environment to reinforce your understanding.
