[![](https://img.shields.io/pypi/pyversions/lowerdict.svg?longCache=True)](https://pypi.org/project/lowerdict/)
[![](https://img.shields.io/pypi/v/lowerdict.svg?maxAge=3600)](https://pypi.org/project/lowerdict/)
[![Travis](https://api.travis-ci.org/looking-for-a-job/lowerdict.py.svg?branch=master)](https://travis-ci.org/looking-for-a-job/lowerdict.py/)

#### Install
```bash
$ [sudo] pip install lowerdict
```

#### Functions
function|`__doc__`
-|-
`lowerdict.lowerdict(*args, **kwargs)`|return dict with lowercase keys

#### Examples
```python
from lowerdict import lowerdict

# lowerdict(*args, **kwargs)
lowerdict({"KEY": "value", "KEY2": "value2"})
>>> {"key": "value", "key2": "value2"}
```

<p align="center"><a href="https://pypi.org/project/readme-md/">readme-md</a> - README.md generator</p>