# Autonomous-vehicle-path-detection-using-ML-methods

## Project Overview

This project addresses one of the major challenges in the development of fully autonomous vehicles: precise path detection for reliable and efficient navigation. We investigate the feasibility of using machine learning methods to enhance path identification accuracy and efficiency under challenging driving conditions.

## Objectives

- **Evaluate Machine Learning Models**: Train and evaluate different machine learning models for path recognition using real-world sensor data from the ONCE Dataset.
- **Analyze Pros and Cons**: Examine the advantages and disadvantages of employing machine learning-based algorithms for real-time navigation in autonomous cars.
- **Enhance Safety and Efficiency**: Improve the safety, efficiency, and regulatory compliance of autonomous vehicle path detection through advanced machine learning techniques.

## Beneficiaries

The findings of this study will benefit:
- Manufacturers of autonomous vehicles
- Transportation authorities
- The academic community


## Research Strategy

1. **Data Collection**: Gather real-world sensor data from the ONCE Dataset.
2. **Data Cleaning**: Process and clean the data for analysis.
3. **Algorithm Vetting**: Evaluate potential machine learning algorithms for path detection.
4. **Model Building**: Develop and train machine learning models.
5. **Model Testing**: Test the models and critique their performance.
6. **Performance Analysis**: Analyze the results and refine the models as needed.

### Imports

- **Data Plotting**: `matplotlib.pyplot`, `matplotlib.patches`
- **Numerical Computations**: `numpy`
- **Data Manipulation and Analysis**: `pandas`
- **Autonomous Vehicle Dataset**: `l5kit`
- **Progress Display**: `tqdm`
- **Element Counting**: `collections.Counter`
- **Table Formatting**: `prettytable`
- **OS Interaction**: `os`
- **Plot Animation**: `matplotlib.animation`

### Functionality

#### `set_seed` Function

The `set_seed` function seeds the numpy random number generator and the Python hash function with the same input. It also sets the `PYTHONHASHSEED` environment variable to the seed value. Although lines for establishing the seed in the `random` and `torch` libraries are included, they are currently commented out and inactive.
veness of autonomous navigation by utilizing machine learning algorithms to advance autonomous vehicle technology. By focusing on real-world applications and challenging driving conditions, this research contributes to the ongoing development and deployment of fully autonomous vehicles.

