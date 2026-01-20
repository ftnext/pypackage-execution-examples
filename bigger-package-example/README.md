Run `mypkg/__main__.py`:

```
% python -m mypkg                       
__main__.py
Awesome ✨
```

Run `__main__` block in `mypkg/awesome.py`:

```
% python -m mypkg.awesome
awesome.py
Awesome ✨
```

Run `mypkg/fabulous/__main__.py` (not `__main__` block in `mypkg/fabulous/__init__.py`):

```
% python -m mypkg.fabulous
__main__.py
Fabulous ✨
```
