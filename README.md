# pac_probability

pac_probability is a package developed to calculate and plot gaussian, binomial and general probabilitiy distribution. It is published on python package index(PyPi). 

## Setup

To run:
```
pip install pac-probability
```
Package will be installed on the system with default version i.e 0.1 using pip. The ```-``` used in place of ```_``` because PyPi takes doesn't take into account ```_```. PyPi uses ```-``` only.

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
