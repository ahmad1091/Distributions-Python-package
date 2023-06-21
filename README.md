# Distributions-Python-package
### convert the modularized code into a Python package

you can put your code into the 3a_python_package folder in the workspace. Inside the 3a_python_package folder, you'll need to create a few folders and files:
* a `setup.py` file, which is required in order to use pip install
* a folder called `'distributions'`, which is the name of the Python package
* inside the `'distributions'` folder, you'll need the `Gaussiandistribution.py` file, `Generaldistribution.py` and an `__init__.py` file.

Once everything is set up, open a new terminal window in the workspace. Then type:

`pip install .`

If everything is set up correctly, pip will install the distributions package into the workspace. You can then start the python interpreter from the terminal typing:
python

Then within the Python interpreter, you can use the distributions package:
from distributions import Gaussian

```
gaussian_one = Gaussian(25, 2)
gaussian_one.mean
gaussian_one + gaussian_one
```