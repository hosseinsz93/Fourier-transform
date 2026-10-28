# Fourier Transform Visualization

This project demonstrates how a piecewise hat function can be approximated with
a Fourier series. The included Jupyter notebook computes the Fourier
coefficients numerically and provides an interactive slider for visualizing the
approximation with different numbers of terms.

## Requirements

- Python 3
- Jupyter Notebook or JupyterLab
- NumPy
- Matplotlib
- `ipywidgets`
- `ipympl`

Install the Python dependencies with:

```bash
pip install numpy matplotlib ipywidgets ipympl
```

## Usage

1. Start Jupyter:

   ```bash
   jupyter notebook
   ```

2. Open [`fourier.ipynb`](./fourier.ipynb).
3. Run all cells.
4. Use the **Terms** slider to change the number of Fourier terms used in the
   approximation.

The notebook plots the original function alongside its Fourier-series
approximation. It uses Matplotlib's widget backend, so an interactive notebook
environment is required for the slider.

## How it works

The notebook:

1. Defines a piecewise hat function over `[-π, π]`.
2. Approximates the Fourier coefficients numerically using a discrete grid.
3. Reconstructs the function from the constant term and sine/cosine terms.
4. Displays the approximation for between 1 and 50 terms.
# Fourier-transform
