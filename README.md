pip-pop: tools for managing requirements files
---

Working with lots of `requirements.txt` files can be bit annoying.
Have no fear, __pip-pop__ is here!

(work in progress)

Planned Commands
---

```Bash
$ pip-diff [--fresh | --stale] <reqfile> <reqfile>
```

Generates a diff between two given requirements files.
Lists either stale or fresh packages.

```Bash
$ pip-flatten [--unsorted] <reqfile> [output]
```

Takes a single requirements file, and expands it.
Essential when working with included files.
Will potentially support blacklisting modules (wsgiref, distribute, setuptools).

Possible Future Commands
---

```Bash
$ pip-where
```
