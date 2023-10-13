# generic-jupyter-env-seaborn

```sh
poetry install
poetry run python -m ipykernel install --user --name generic-jupyter-env-seaborn
```

- May have to run this in emacs to have the kernel update
```lisp
(jupyter-available-kernelspecs 'refresh)
```

- Consider having this in a org file

```org
# -*- org-download-image-dir: "figures"; -*-
#+PROPERTY: header-args:jupyter-python :kernel generic-jupyter-env-seaborn  :exports both
```
