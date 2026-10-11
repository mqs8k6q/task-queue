# task-queue

A bounded worker pool with backpressure, retries and graceful shutdown.

## Why

Written while learning the language properly, and kept because it still works.

## Install

```bash
pip install task-queue
```

## Usage

```python
from task_queue import taskQueue

result = taskQueue("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
