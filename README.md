# passerts
This library contains a collection of assert utilities to make python code more secure.

```
pip install passerts
```


1. check object not None before using it
```python
  obj = passerts.asserts.not_none(obj)
```

2. get list element safely:
```python
  alist = [1, 2, 3]
  elem = passerts.asserts.safe_get(alist, 2)
```
