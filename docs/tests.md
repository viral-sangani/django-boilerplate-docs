---
id: tests
title: Tests
sidebar_label: Testing
---

We encourage users to build application tests.

### Pytest

This project uses the [Pytest](https://docs.pytest.org/en/latest/example/simple.html), a framework for easily building simple and scalable tests. After you have set up to develop locally, run the following commands to make sure the testing environment is ready:

```bash
pytest
```

### Coverage

You should build your tests to provide the highest level of code coverage. You can run the pytest with code coverage by typing in the following command:

```bash
coverage run -m pytest
coverage html
```
