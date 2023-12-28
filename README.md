MEAN-VARIANCE-STANDARD DEVIATION CALCULATOR


Create a function named calculate() in mean_var_std.py that uses Numpy to output the mean, variance, standard deviation, max, min, and sum of the rows, columns, and elements in a 3 x 3 matrix.

The input of the function should be a list containing 9 digits. The function should convert the list into a 3 x 3 Numpy array, and then return a dictionary containing the mean, variance, standard deviation, max, min, and sum along both axes and for the flattened matrix.


## Usage

1. Ensure you have Python installed on your system.
2. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/GunjanPasricha/MVSD-calculator.git
    ```

3. Navigate to the project directory:

    ```bash
    cd your-repository
    ```

4. Open a Python environment (e.g., Jupyter notebook, Python script) and import the `calculate` function:

    ```python
    from calculator import calculate
    ```

5. Create a 3x3 matrix represented as a list of nine numbers and call the `calculate` function:

    ```python
    result = calculate([0, 1, 2, 3, 4, 5, 6, 7, 8])
    print(result)
    ```

    Replace the list with your own set of nine numbers.
   ## Functionality

The `calculate` function performs the following calculations on the input 3x3 matrix:

- **Mean:** Calculates the mean along each axis and overall.
- **Variance:** Calculates the variance along each axis and overall.
- **Standard Deviation:** Calculates the standard deviation along each axis and overall.
- **Maximum:** Finds the maximum value along each axis and overall.
- **Minimum:** Finds the minimum value along each axis and overall.
- **Sum:** Calculates the sum along each axis and overall.

## Example

    ```python
from calculator import calculate

result = calculate([0, 1, 2, 3, 4, 5, 6, 7, 8])
print(result)

   License

This project is licensed under the MIT License - see the LICENSE file for details.




