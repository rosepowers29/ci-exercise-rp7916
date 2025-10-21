# Changelog

### Fixes in src/unc/\_\_init\_\_.py
- Added a \_\_hash()\_\_ method
- Removed non-unicode "delta" characters and replaced variable name with delta_c

### Fixes in tests/test_stdunc.py
- Now passes ("a", "b") as a tuple instead of "a,b"
