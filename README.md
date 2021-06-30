# SceneLang Highlighter

This extension provides syntax highlighting for the SceneLang Domain-Specific Language (DSL), as defined at the Julia package [Raytracer.jl](https://github.com/Paolo97Gll/Raytracer.jl). We suggest to check its documentation section about the language.

## Features

- Syntax Highliting
	- Distinguishes scene-related commands, instruction commands, and construction commands
	- Marks as invalid all non-existing commands
	- Distinguishes type-extension keywords, attribute keywords, and command extension keywords
	- Marks as invalid all non-constructing keywords following a lowercase letter
	- In math expression marks as invalid identifiers preceded by a dot

> **Note:** for devevelopers. If any commands are added to the language add them in the `syntaxes/scenelang.tmLanguage.json` file too.

Here reported is a screenshot of how the syntax highlighting would appear when using the `Dark+` VSCode theme.

![feature X](images/scenelang_highlighting_example.png)

## Release Notes

### 0.1.3
Add `TIME` command highlighting

### 0.1.2

Fix some highlighting issues
- identifiers in math expressions
- words starting with an underscore are identifiers, not commands

### 0.1.1

Day One hotfixes

### 0.1.0

Initial release
