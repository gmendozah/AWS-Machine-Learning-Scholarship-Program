# Making a Package and Pip Installing

Contents:
* a setup.py file, which is required in order to use pip install
* a folder called 'distributions', which is the name of the Python package
* inside the 'distributions' folder, you'll need the Gaussiandistribution.py file, Generaldistribution.py and an __init__.py file.


## Run
In a terminal or command window, navigate to the top-level project directory `cd package/` (that contains this README) and run the following command:

```bash
pip install .
```

```bash
python
```

```bash
from distributions import Gaussian
gaussian_one = Gaussian(25, 2)
gaussian_one.mean
gaussian_one + gaussian_one

```



## License

This project uses the [MIT](https://choosealicense.com/licenses/mit/) License.