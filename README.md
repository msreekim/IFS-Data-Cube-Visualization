# IFS-Data-Cube-Visualization

Visualization of MaNGA galaxy data cube using Integral Field Spectroscopy (IFS)

This project demonstrates how to visualize MaNGA galaxy FITS data cubes using Integral Field Spectroscopy (IFS). The notebook helps analyze the structure of galaxies by examining flux values across spatial and spectral dimensions.

---

## 📊 Features

- Reads and inspects 3D FITS files
- Visualizes 2D slices at different wavelengths
- Extracts and plots spectra at specific pixels (spaxels)
- Enables spectral analysis of galaxies using IFS data

---

## 🛰️ Dataset

- **File:** `manga-10215-1902-LINCUBE.fits`
- **Redshift:** 0.0259
- **Source:** MaNGA (Mapping Nearby Galaxies at Apache Point Observatory)

> **Note:** The FITS data cube is too large to store in this repository.

You can download it from the link below and use it with the notebook.

🔗 **[Download FITS file from Google Drive](https://drive.google.com/file/d/1o3ecl3qBPA02hLzz0AmDDUKUye6rh35K/view?usp=sharing)**  

Once downloaded, make sure to mount your Google Drive (if using Colab) and update the file path accordingly in the notebook.

---

## 🧰 Requirements

To run this notebook, install the following Python packages:

- `astropy`
- `matplotlib`
- `numpy`

You can install them via pip:

```bash
pip install astropy matplotlib numpy
