# ALX Backend Python - Unittests and Integration Tests

## Learning Objectives
- Understand the difference between unit and integration tests.
- Familiarity with common testing patterns: mocking, parametrizations, and fixtures.

## Requirements
- Ubuntu 18.04 LTS using Python3 (version 3.7)
- All files should end with a new line
- First line: `#!/usr/bin/env python3`
- Mandatory `README.md` file
- Code should use pycodestyle style (version 2.5)
- All files must be executable
- All modules, classes, and functions must have documentation
- Functions and coroutines must be type-annotated.

## Required Files
1. `utils.py` (or download)
2. `client.py` (or download)
3. `fixtures.py` (or download)

### Tasks

#### 0. Parameterize a unit test
- Create `TestAccessNestedMap` class.
- Implement `TestAccessNestedMap.test_access_nested_map` method with `@parameterized.expand`.

#### 1. Parameterize a unit test
- Implement `TestAccessNestedMap.test_access_nested_map_exception` using `assertRaises`.

#### 2. Mock HTTP calls
- Define `TestGetJson(unittest.TestCase)` class.
- Implement `TestGetJson.test_get_json` to test `utils.get_json` with patched HTTP calls.

#### 3. Parameterize and patch
- Implement `TestMemoize(unittest.TestCase)` class with `test_memoize` method using memoization and patching.

#### 4. Parameterize and patch as decorators
- Declare `TestGithubOrgClient(unittest.TestCase)` class in `test_client.py`.
- Implement `test_org` method to unit-test `GithubOrgClient.org` with patching.

#### 5. Mocking a property
- Implement `test_public_repos_url` method to unit-test `GithubOrgClient._public_repos_url` using property mocking.

#### 6. More patching
- Implement `TestGithubOrgClient.test_public_repos` to unit-test `GithubOrgClient.public_repos` with patching.

#### 7. Parameterize
- Implement `TestGithubOrgClient.test_has_license` to unit-test `GithubOrgClient.has_license` with parametrization.

#### 8. Integration test: fixtures
- Create `TestIntegrationGithubOrgClient(unittest.TestCase)` class.
- Implement `setUpClass` and `tearDownClass` for integration testing using fixtures.

## Copyright
Copyright © 2024 ALX, All rights reserved.
