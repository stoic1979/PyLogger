# PyLogger
A singleton logger that will be used globally by the project

# Notes
- This logger runs in python3.
- You can change the format of log messages to your desired one.

# Sample usage
```python
from logger import get_logger
log = get_logger()
log.info("hello navi")
log.debug("its some debug msg")
```
