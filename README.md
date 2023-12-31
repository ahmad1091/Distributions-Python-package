# Distributions-Python-package
### convert the modularized code into a Python package


* a `setup.py` file, which is required in order to use pip install
* a folder called `'distributions'`, which is the name of the Python package
* inside the `'distributions'` folder, you'll need the `Gaussiandistribution.py` file, `Generaldistribution.py` and an `__init__.py` file.
* test.py unit tests to help you debug your code
- `numbers.txt` and `numbers_binomial.txt` are data files used as part of the unit tests
- `Binomialdistribution_challenge.py`

Once everything is set up, open a new terminal window in the workspace. Then type:

`pip install .`

If everything is set up correctly, pip will install the distributions package into the workspace. You can then start the python interpreter from the terminal typing:
python

Then within the Python interpreter, you can use the distributions package:

```
from distributions import Gaussian
gaussian_one = Gaussian(25, 2)
gaussian_one.mean
gaussian_one + gaussian_one
```
from Gu_Bi_GB import Gaussian
To run the **unit tests** by typing `python -m unittest test`