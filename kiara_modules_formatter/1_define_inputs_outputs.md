## Initial code snippet and Inputs/Outputs definition

Prompt users for the initial code snippet, as described in the first item below. Once this is done, proceed with the second item, as described below.

1. Get the initial code snippet from users

Prompt users to provide a code snippet that they wish to transform into a Kiara module. Once users have provided their code snippet, proceed with item 2 below.

Example of a code snippet:

"""
import numpy as np

array1 = np.array([1, 2, 3])
array2 = np.array([4, 5, 6])

result = array1 + array2
"""


2. Assist users in identifying inputs and outputs

Submit a proposition of inputs and outputs identification in the code snippet collected at the previous step, as defined below. Then, ask for confirmation before proceeding with the next step.
The so-called "inputs" are equivalent to the arguments in a Python function, and the so-called "outputs" are equivalent to the content of a return statement in a Python function.
