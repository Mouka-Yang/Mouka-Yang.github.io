---
title: 合并两个字典
categories:
- Python Tricks
feature_image: "https://picsum.photos/2560/600?image=872"
---
<!-- more -->

 **Python 版本 &gt; 3.5**

```python
>>> x = {'a': 1, 'b': 2}
>>> y = {'b': 3, 'c': 4}

>>> z = {**x, **y}    # 一行代码合并两字典
>>> z
{'c': 4, 'a': 1, 'b': 3}
```

**Python 版本 2.x**

```python
>>> x = {'a': 1, 'b': 2}
>>> y = {'b': 3, 'c': 4}

>>> z = dict(x, **y)
>>> z
{'a': 1, 'c': 4, 'b': 3}
```

