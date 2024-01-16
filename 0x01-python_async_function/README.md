# ALX Backend Python - Async Specialization

## Overview

Welcome to the ALX Backend Python Async Specialization project. This curriculum focuses on asynchronous programming in Python, emphasizing key concepts and practical applications. Below is an overview of the project structure and tasks.

### Curriculum

#### Short Specializations

The specialization covers Python, specifically focusing on back-end development. The modules are curated by Emmanuel Turlay, a seasoned Staff Software Engineer at Cruise. The weight assigned to this specialization is 1, indicating its significance in the curriculum.

#### Resources

Students are encouraged to explore relevant resources, including "Async IO in Python: A Complete Walkthrough," documentation on asyncio, and the random.uniform function.

#### Learning Objectives

Upon completion of this project, students should master the following concepts without relying on external assistance:
- Understanding async and await syntax
- Executing an async program using asyncio
- Running concurrent coroutines
- Creating asyncio tasks
- Utilizing the random module effectively

### Requirements

To maintain consistency and code quality, specific requirements are set:
- A mandatory `README.md` file at the project root
- Allowed editors include `vi`, `vim`, and `emacs`
- Code interpreted/compiled on Ubuntu 18.04 LTS using Python 3.7
- Files following specified conventions (shebang, line endings, executability)
- Adherence to `pycodestyle` style (version 2.5.x)
- Type annotations for functions and coroutines
- Documentation for modules and functions using `python3 -c 'print(__import__("my_module").__doc__)'`

### Tasks

#### 0. The basics of async

This task involves writing an asynchronous coroutine, `wait_random`, that introduces students to the fundamental concepts of async programming using the random module.

#### 1. Let's execute multiple coroutines at the same time with async

The task requires importing `wait_random` and creating an async routine, `wait_n`, to spawn multiple concurrent coroutines, showcasing the power of async execution.

#### 2. Measure the runtime

Students are expected to measure the total execution time of the `wait_n` function and return the average time per coroutine, providing insights into the efficiency of async operations.

#### 3. Tasks

In this task, a non-async function, `task_wait_random`, is implemented to return an asyncio.Task object, demonstrating the integration of async functionality.

#### 4. Tasks

Building on the previous task, `task_wait_n` is introduced, illustrating the adaptation of code from `wait_n` to handle asyncio tasks.

## Copyright

© 2024 ALX. All rights reserved.
