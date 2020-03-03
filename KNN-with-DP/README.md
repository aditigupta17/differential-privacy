This is the implementation of KNN with DP

This folder contains the file `pairwise.py` which has the modification of scikit-learn package to include this functionality. The implementational idea is to **_add Gaussian noise to the euclidean distance algorithm_**

To use the code, replace the file in the `sklearn/metrics/pairwise.py` location with this file. (To get to know the location of sklearn in your system, `import sklearn` and `print(sklearn.__file__)`)

## TODO:
- The current implementation is done directly in the core euclidean distance function itself. We need to move it out of there and put it in a separate function.
-  The gaussian noise has fixed variance. It needs to be parameterised.
