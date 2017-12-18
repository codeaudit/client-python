# RiseML Client Library for Python

This repository contains the RiseML client library for Python.

## Install
You can use pip to install the library:

```
pip install git+https://github.com/riseml/riseml-python.git@v1.0.0 
```

## Reporting Experiment Results

To report experiment results:

```python
import riseml

riseml.report_result(accuracy=evaluation[1])
```
