---
title: 内置 http 服务器
categories:
- Python Tricks
feature_image: "https://picsum.photos/2560/600?image=872"
---
<!-- more -->

```python
# Python has a HTTP server built into the
# standard library. This is super handy for
# previewing websites.

# Python 3.x
$ python3 -m http.server

# Python 2.x
$ python -m SimpleHTTPServer 8000

# (This will serve the current directory at
#  http://localhost:8000)
```



