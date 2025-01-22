[![codecov](https://codecov.io/github/hankunxiao/pycounts/graph/badge.svg?token=TXQV0KA181)](https://codecov.io/github/hankunxiao/pycounts)

# pycounts

Calculate word counts in a text file!

Author: Hankun Xiao

## Installation

```bash
pip install -i https://test.pypi.org/simple/ pycounts_hankun_xiao
```

## Usage

`pycounts` can be used to count words in a text file and plot results
as follows:

```python
from pycounts_hankun_xiao.pycounts_hankun_xiao  import count_words
from pycounts_hankun_xiao.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. 
Please note that this project is released with a Code of Conduct. 
By contributing to this project, you agree to abide by its terms.

## License

`pycounts` was created by Tomas Beuzen. It is licensed under the terms
of the MIT license.

## Credits

`pycounts` was created with 
[`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and 
the `py-pkgs-cookiecutter` 
[template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
