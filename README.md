# TensorFlow-in-Python
This repository contains a course on TensorFlow in Python, covering the basics of TensorFlow, working with constants and variables, performing operations, and building linear models.
#Introduction to TensorFlow
**Importing TensorFlow and Creating Constants
-We start by importing the constant function from TensorFlow and converting a NumPy array to a TensorFlow constant:
from tensorflow import constant

credit_constant = constant(credit_numpy)

print('\nThe datatype is:', credit_constant.dtype)
print('\nThe shape is:', credit_constant.shape)
