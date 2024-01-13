# How to run

## Clone

```shell
% git clone git@github.com:ftnext/pypackage-execution-examples.git
% cd run-module-antipattern
% pip install -e .

% python awesomelib/cli.py
Awesome ✨
```

## Install

```shell
% # Install from GitHub
% pip install 'awesomelib@git+https://github.com/ftnext/pypackage-execution-examples#subdirectory=run-module-antipattern'

% # Run module
% python $(python -c 'import site; print(site.getsitepackages()[0])')/awesomelib/cli.py
Awesome ✨
```
