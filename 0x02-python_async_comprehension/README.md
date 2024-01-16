# ALX Backend Python - Async Comprehension Specialization

## Overview

Welcome to the ALX Backend Python Async Comprehension Specialization project. This curriculum, under the guidance of Emmanuel Turlay, a distinguished Staff Software Engineer at Cruise, delves into asynchronous programming with a focus on comprehension techniques. Here's an overview of the project structure and tasks.

### Curriculum

#### Short Specializations

This specialization centers around Python, specifically in back-end development. Emmanuel Turlay's expertise ensures a comprehensive learning experience. The project holds a weight of 1, highlighting its significance in the curriculum.

#### Resources

Students are encouraged to explore key resources, including PEP 530, insights into asynchronous comprehensions/generators in Python, and type hints for generators.

#### Learning Objectives

Upon completing this project, students are expected to independently explain the following concepts:
- Writing an asynchronous generator
- Utilizing async comprehensions
- Type-annotating generators effectively

### Requirements

To maintain code quality and consistency, specific requirements are set:
- Allowed editors include `vi`, `vim`, and `emacs`
- Code interpreted/compiled on Ubuntu 18.04 LTS using Python 3.7
- Files following specified conventions (shebang, line endings)
- A mandatory `README.md` file at the project root
- Code adhering to the `pycodestyle` style (version 2.5.x)
- Length of files tested using `wc`
- Modules and functions documented (`python3 -c 'print(__import__("my_module").__doc__)'`)
- Type annotations for functions and coroutines

### Tasks

#### 0. Async Generator (mandatory)

In this task, students are required to write a coroutine, `async_generator`, that loops 10 times, asynchronously waits for 1 second on each iteration, and yields a random number between 0 and 10 using the `random` module.

```python
bob@dylan:~$ cat 0-main.py
#!/usr/bin/env python3

import asyncio

async_generator = __import__('0-async_generator').async_generator

async def print_yielded_values():
    result = []
    async for i in async_generator():
        result.append(i)
    print(result)

asyncio.run(print_yielded_values())
```

**Repo:**

GitHub repository: [alx-backend-python](#)

Directory: [0x02-python_async_comprehension](#)

File: [0-async_generator.py](#)

#### 1. Async Comprehensions (mandatory)

The task involves importing `async_generator` from the previous task and writing a coroutine, `async_comprehension`, to collect 10 random numbers using an async comprehension over `async_generator`, then return the list of 10 random numbers.

```python
bob@dylan:~$ cat 1-main.py
#!/usr/bin/env python3

import asyncio

async_comprehension = __import__('1-async_comprehension').async_comprehension

async def main():
    print(await async_comprehension())

asyncio.run(main())
```

**Repo:**

GitHub repository: [alx-backend-python](#)

Directory: [0x02-python_async_comprehension](#)

File: [1-async_comprehension.py](#)

#### 2. Run time for four parallel comprehensions (mandatory)

Students are required to import `async_comprehension` from the previous file and write a `measure_runtime` coroutine that executes `async_comprehension` four times in parallel using `asyncio.gather`. The task aims to measure the total runtime and return it.

```python
bob@dylan:~$ cat 2-main.py
#!/usr/bin/env python3

import asyncio

measure_runtime = __import__('2-measure_runtime').measure_runtime

async def main():
    return await measure_runtime()

print(
    asyncio.run(main())
)
```

**Repo:**

GitHub repository: [alx-backend-python](#)

Directory: [0x02-python_async_comprehension](#)

File: [2-measure_runtime.py](#)

## Copyright

© 2024 ALX. All rights reserved.
