# NDVI Precipitation Analysis

This repository contains Jupyter notebooks for analyzing precipitation datasets related to El Salvador.

## Notebook location
- `notebooks/analisis_precipitacion_sv.ipynb`

## How to open the notebook in Google Colab
1. Download or clone this repository so you have the `notebooks/analisis_precipitacion_sv.ipynb` file locally.
2. Visit [Google Colab](https://colab.research.google.com/).
3. Click **File → Upload notebook** and choose the `analisis_precipitacion_sv.ipynb` file from the `notebooks/` folder.
4. (Optional) If the Colab runtime lacks `xarray`, install it in a cell with `!pip install xarray` before running the notebook.
5. Adjust the parameters (years, latitude/longitude) in the first cells as needed and run the notebook cells in order.

## Additional notes
- The notebook downloads CHIRPS precipitation data directly from ERDDAP, so ensure the runtime has internet access.
- For reproducibility, consider saving the processed datasets or figures after running the notebook.
