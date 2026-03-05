# minify-css

> Minify CSS with simple Python

[![PyPI version](https://badge.fury.io/py/minify-css.svg)](https://pypi.org/project/minify-css/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org)

## Installation

```bash
pip install minify-css
```

## Quick Start

```python
from minify_css import css

# Basic usage
result = css("your input here")
print(result)
```

## Features

- Simple, clean API with type hints
- Zero dependencies (pure Python)
- Python 3.8+ compatible
- Fully tested
- Lightweight (< 5KB)

## API Reference

### `css(input)`

Main utility function.

**Parameters:**
- `input` — The input data to process

**Returns:** Processed result

### `batch(inputs)`

Process multiple inputs at once.

**Parameters:**
- `inputs` — List of inputs

**Returns:** List of results

## Examples

```python
from minify_css import css

# Example 1: Basic usage
result = css("Hello World")

# Example 2: Batch processing
from minify_css import batch
results = batch(["item1", "item2", "item3"])
```

## Running Tests

```bash
pip install pytest
pytest tests/
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT License - see [LICENSE](LICENSE) file for details.

---

### Learn More

**Want to build tools like this?** Check out the
**[Website From Scratch](https://gumroad.com/l/website-from-scratch)** course — it teaches you
step-by-step how to create useful Python utilities from scratch,
with real-world projects and best practices.

*Built with skills from [Website From Scratch](https://gumroad.com/l/website-from-scratch)*
