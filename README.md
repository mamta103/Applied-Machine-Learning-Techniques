# Applied-Machine-Learning-Techniques
from sklearn import datasets

# Classification datasets
iris = datasets.load_iris()              # Flower species (150 samples)
wine = datasets.load_wine()              # Wine classification (178 samples)
breast_cancer = datasets.load_breast_cancer()  # Cancer diagnosis (569 samples)
digits = datasets.load_digits()          # Handwritten digits (1797 samples)

# Regression datasets
diabetes = datasets.load_diabetes()      # Diabetes progression (442 samples)
california_housing = datasets.fetch_california_housing()  # House prices
boston = datasets.load_boston()          # DEPRECATED (don't use)

# Other datasets
linnerud = datasets.load_linnerud()      # Physical exercise data

print("All datasets loaded successfully! ✅")
