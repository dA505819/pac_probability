# pac_probability [![PyPI version](https://badge.fury.io/py/pac-probability.svg)](https://badge.fury.io/py/pac-probability)

pac_probability is a package developed to calculate and plot gaussian, binomial and general probabilitiy distribution.

## Setup

To run:
```
pip install pac-probability
```
Package will be installed on the system with default version 0.1 using pip. The ```-``` used in place of ```_``` because PyPi doesn't take into account ```_```. PyPi uses ```-``` only. The name of the package **pac_probability** remains same.

Then type,
```
from pac_probability import Gaussian, Binomial

Gaussian(12,8)
```
The output mean is 12 and standard deviation is 8.

Also, run:
```
Binomial(0.8, 21)
```
The output mean is 16.8, standard deviation is 1.8330302779823358, p is 0.8 and n is 21.

# License
[MIT](https://github.com/dA505819/pac_probability/blob/master/LICENSE)
