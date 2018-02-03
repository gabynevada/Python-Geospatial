# Numpy
## Install Numpy
+ Open a Command Prompt window
+ Type the following command
```
python -m pip install numpy
```
## Test Numpy Installation
+ Open the python command line or equivalent
+ To open the python command line in the Command Prompt type:
```
python
```
+ Run the following code
``` python
import numpy as np
a = np.arange(15).reshape(3, 5)
print a.shape
```
+ The print result must be **(3L, 5L)**
+ If correct then numpy installation was succesful
