# rtSNE
A repository with a repeatable version of t-SNE.

Example use

```python
from rtSNE import rtSNE

my_repeatable_tSNE = rtSNE(n_components=2)
my_repeatable_tSNE.fit(X)

X_reduced = my_repeatable_tSNE.transform(X)
```
For a detailed writeup, check out https://bshabashfd.github.io/2019/12/27/reusable-tsne.html
