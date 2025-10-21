# Changelog

### Fixes in src/unc/__init__.py
- Added a __hash()__ method
- Removed non-unicode "delta" characters and replaced variable name with delta_c

### Fixes in tests/test_stdunc.py
- Now passes ("a", "b") as a tuple instead of "a,b"
