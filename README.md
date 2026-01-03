# Feature Engineering

A structured collection of Jupyter notebooks covering essential feature engineering techniques for machine learning projects. This repository provides practical implementations using pandas, scikit-learn, and specialized encoding libraries.

## 📚 Table of Contents

### Part 1: Variable Types
Understanding and working with different data types in your datasets.
- `01-variable-type.ipynb` - Introduction to variable types (numerical, categorical, datetime)
- `02-variable-type-conversion.ipynb` - Converting between different variable types

### Part 2: Variable Characteristics
Identifying and addressing common data quality issues.
- `01-missing-values.ipynb` - Detecting and analyzing missing data patterns
- `02-high-cardinality-handling.ipynb` - Managing categorical variables with many unique values
- `03-rare-frequent-labels.ipynb` - Handling rare and frequent category labels
- `04-outlier-handling.ipynb` - Detecting and treating outliers
- `05-model-linearity.ipynb` - Assessing linear relationships in data
- `06-variable-magnitude.ipynb` - Understanding feature scales and magnitudes

### Part 3: Single Variable Imputation
Techniques for filling missing values using univariate methods.
- `01-intro-imputation.ipynb` - Overview of imputation strategies
- `02-imputation-pandas.ipynb` - Imputation using pandas methods
- `03-imputation-sklearn.ipynb` - Imputation with scikit-learn SimpleImputer
- `04-grid-search-imputation.ipynb` - Optimizing imputation strategies with grid search

### Part 4: Multivariate Imputation
Advanced imputation methods using multiple variables.
- `01-intro-multivariate-imputation.ipynb` - Introduction to multivariate imputation
- `02-multivariate-imputer-sklearn.ipynb` - Using scikit-learn's IterativeImputer

### Part 5: Encoding
Converting categorical variables into numerical representations.
- `01-intro-encoding.ipynb` - Overview of encoding techniques
- `02-encoding-pandas.ipynb` - Encoding with pandas (get_dummies, map, replace)
- `03-encoding-sklearn.ipynb` - Encoding with scikit-learn (OneHotEncoder, OrdinalEncoder, LabelEncoder)

### Part 6: Advanced Encoding Techniques
Specialized encoding methods for complex categorical relationships.
- `01-intro-advanced-encoding.ipynb` - Introduction to advanced encoding strategies
- `02-advanced-encoding-category-encoder.ipynb` - Target encoding, weight of evidence, and more using category_encoders library

### Part 7: Variable Transformation
Mathematical transformations to improve feature distributions.
- `01-variable-transformation.ipynb` - Log, square root, reciprocal, and Box-Cox transformations
- `02-variable-transform-sklearn.ipynb` - Transformations using scikit-learn (PowerTransformer, QuantileTransformer)

### Part 8: Discretization
Converting continuous variables into categorical bins.
- `01-discretization.ipynb` - Introduction to binning strategies
- `02-discretization-pandas.ipynb` - Discretization with pandas cut and qcut
- `03-discretization-sklearn.ipynb` - Discretization using scikit-learn KBinsDiscretizer

### Part 9: Mixed Variables
Handling variables that contain multiple data types.
- `01-mixed-variables.ipynb` - Techniques for parsing and splitting mixed-type variables

### Part 10: Feature Creation
Engineering new features from existing variables.
- `01-feature-creation.ipynb` - Creating interaction terms, polynomial features, and domain-specific features

## 🚀 Getting Started

### Prerequisites

```bash
# Required libraries
pip install pandas numpy scikit-learn category-encoders jupyter
```