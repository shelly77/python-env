# ML venv 

Python virtual environments for ML

- [venv](https://docs.python.org/3/library/venv.html)

## Makefile

- run 'make' to get start

## How to use in VS Code

### 1. Easy way:
- Create ./src/ folder
- put your code or repo inside

`command + shift` then type: `Python: Select interpreter`

Select Python from `Python 3.x.x ('.venv':venv)`

### 2. best way:

If your project is not under venv folder, for the first time you need help VS Code find your venv interpreter path.

1. `command + shift` then type: `Python: Select interpreter`
2. Select Enter interpreter path:
    - add your interpreter path.
    - example: `/Users/YOUR_USER_NAME/repo/python-env/.venv/bin/python`

## Python version

change version with homebrew

```
~ % brew unlink python@3.9
Unlinking /opt/homebrew/Cellar/python@3.9/3.9.13_1... 24 symlinks removed.
~ % brew link python@3.8
Linking /opt/homebrew/Cellar/python@3.8/3.8.13_1... 24 symlinks created.
~ % python3 -V
Python 3.8.13
```