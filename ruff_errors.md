# Intentional Ruff Errors

The following 4 errors were introduced in `vibe/core/logger.py` to be caught by `uv run ruff check .`:

| # | Rule | Location | Description |
|---|------|----------|-------------|
| 1 | `I001` | line 1 | Import block unsorted — `import logging` placed before `from datetime import ...` |
| 2 | `F401` | line 8 | `import sys` is unused |
| 3 | `UP035` | line 9 | `from typing import List` is deprecated |
| 4 | `UP006` | line 74 | Return type uses `List[str]` instead of `list[str]` |
