# pywe-exception

Wechat Exception Module for Python.

# Installation

```shell
pip install pywe-exception
```

# Usage

  ```python
  In [1]: from pywe_exception import WeChatException

  In [2]: raise WeChatException({"errcode": 40125, "errmsg": "invalid appsecret, view more at http://t.cn/RAEkdVq hint: [MVpSma0994e544]"})
  ---------------------------------------------------------------------------
  WeChatException                           Traceback (most recent call last)
  <ipython-input-2-793779f73857> in <module>()
  ----> 1 raise WeChatException({"errcode": 40125, "errmsg": "invalid appsecret, view more at http://t.cn/RAEkdVq hint: [MVpSma0994e544]"})

  WeChatException: {'errcode': 40125, 'errmsg': 'invalid appsecret, view more at http://t.cn/RAEkdVq hint: [MVpSma0994e544]'}
  ```

# Method

```python
class WeChatException(Exception):
    """ WeChatException """
```
