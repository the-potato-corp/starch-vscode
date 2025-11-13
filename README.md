# STARCH Language Support

Syntax highlighting and language support for **STARCH**, the primary programming language of [PotatoOS](https://github.com/yourusername/potatoos).

## Features

- **Syntax highlighting** for all STARCH language features
- **Bracket matching** that properly handles strings
- **Auto-closing pairs** for quotes, brackets, and braces
- **Comment toggling** (supports `//`, `#`, `/* */`, and `<!-- -->`)
- **Smart indentation** for STARCH's brace-based blocks
- **File icons** for `.starch` files

## STARCH Highlights

STARCH is a C-styled gradually-typed language with some unique features:

### Pipeline Operator (`~>`)
Transform data fluently without nested function calls:

```starch
"Hello, World!"
	~> .trim()
	~> .upper()
	~> .replace(" ", "_")
	~> print();
```

### Flexible Identifiers
Variables can contain almost any character except reserved operators:

```starch
var is-valid? = true;
var user_name! = "Edward";
```

### Multiple Comment Styles
Choose your preferred syntax:

```starch
// JavaScript-style
# Python-style
/* Block comments */
<!-- HTML-style blocks -->
```

### Approximate Equality (`≈`)
Built-in fuzzy comparison for numbers (within 10%) and case-insensitive strings:

```starch
var close-enough = (50 ≈ 54);  // true
```

## Installation

Install directly from the VS Code Marketplace or run:

```bash
code --install-extension PotatoCorp.starch-language-support
```

## About STARCH

STARCH is the scripting language for PotatoOS, a portable operating system built on the Godot Engine. It combines familiar C-style syntax with modern conveniences like pipeline operators and gradual typing.

Learn more:
- [STARCH Documentation](https://github.com/yourusername/potatoos/wiki/starch)
- [PotatoOS Project](https://github.com/yourusername/potatoos)

## Contributing

Found a bug or want to add a feature? Issues and pull requests are welcome!

## License

MIT License - see [LICENSE](LICENSE) for details.

---

**Enjoy coding in STARCH!** 🥔
