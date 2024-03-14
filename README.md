<h1 align="center">
	🚀 Minishell
</h1>

<p align="center">
	<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/JBVer/Minishell?color=lightblue" />
	<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/JBVer/Minishell?color=blue" />
	<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/JBVer/Minishell?color=green" />
</p>

## 💡 About the project
* This project aimed to create a Unix shell mirroring bash's behavior.

## Built-ins Implemented
* `echo`: Supports the `-n` option.
* `cd`: Allows for changing the current working directory using relative or absolute paths.
* `pwd`: Displays the current working directory.
* `export`: Manages environment variables without any options.
* `unset`: Removes environment variables without any options.
* `env`: Displays the environment variables or arguments.
* `exit`: Exits the shell without any options.

## Features
- ``CTRL-C``
- ``CTRL-\``
- ``CTRL-D``
- ``|`` pipes
- ``;`` semicolons
- ``>`` ``>>`` ``<`` ``<<`` redirections
- ``&&`` ``||`` operators
- ``*`` wildcard
- local variable
- env expansions + ``$?``

## Usage

```shell
# Within the Project dir; Compile
make

# Launch the shell
./minishell
```

## Authors
- Niels Schmitt
- Jean-Baptiste Vermeersch
