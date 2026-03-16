# pycache-manager

A Python toolkit for managing, analyzing, and cleaning __pycache__ directories across your projects.

## Features
- Scan directories for cache files
- Analyze cache size and age
- Safe cache cleanup with dry-run mode
- Cross-platform support

## Installation
```bash
pip install pycache-manager
```

## Quick Start
```python
from pycache_manager import CacheScanner

scanner = CacheScanner('./my-project')
scanner.scan()
scanner.report()
```