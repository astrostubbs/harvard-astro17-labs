# Harvard Astro 17: Extragalactic Astronomy Lab Notebooks

Instructional Colab notebooks for Harvard's Fall 2025 introductory extragalactic astronomy and cosmology course.

## Overview

These Google Colab notebooks provide hands-on computational exercises covering topics from stellar populations to cosmological distance measurements. All notebooks run on **Google Colab** with no local installation required.

## Quick Start

1. Download the data files from the `data/` folder
2. Upload them to your Google Drive's `Colab Notebooks` folder
3. Open any notebook from `notebooks/` in Google Colab
4. Mount your Google Drive when prompted
5. Run the cells!

## Notebooks

| Notebook | Topic | Data Required |
|----------|-------|---------------|
| `Gaussians.ipynb` | Statistical fitting and distributions | None |
| `Linear_Regression_Correlation.ipynb` | Regression and parameter correlation | None |
| `Distances.ipynb` | Cosmological distance measures | None |
| `FIRASfit.ipynb` | CMB blackbody spectrum fitting | None (embedded) |
| `gaia.ipynb` | HR diagram with Gaia data | `gaia_200pc_sample.fits` |
| `Galaxy_Rotation_Curve_Fitting.ipynb` | Dark matter and rotation curves | None (embedded) |
| `LineProfileGalaxies.ipynb` | Galaxy morphology profiles | Multiple FITS images |
| `NumberCounts.ipynb` | Galaxy counts and star-galaxy separation | `A1942nohead.tsv` |
| `ClusterLRG_Rubin.ipynb` | Galaxy clusters with Rubin data, photoz's | `abell360_...fits` |
| `Zshell.ipynb` | Galaxy spatial distributions | `sdss_photometry.csv` |
| `SN1a_Hubble_Fit.ipynb` | Hubble diagram fitting, evidence for dark energy | None (embedded) |
| `Diffraction_Grating_Lab.ipynb` | Spectroscopy lab | Student-provided images |

## Data Files

All data files are in the `data/` directory. Total size: ~75 MB.

## Google Colab Notes

**Benefits:**
- No local Python installation needed
- Works on any computer with a web browser
- Pre-installed scientific libraries

**Important:**
- Data files must be in your Google Drive
- `pip install` commands don't persist between sessions
- Save work frequently (Colab times out after inactivity)

## Requirements

For local use (optional):
```bash
pip install -r requirements.txt
```

## Documentation

See `Astro17_instructor_guide_for_notebooks.pdf` for detailed notebook descriptions, learning objectives, and setup instructions.

## Author

Christopher Stubbs
Harvard University
stubbs@g.harvard.edu

## Astronomical Survey Data Used

These notebooks use associated image and catalog data from SDSS, the Pantheon SN survey, Rubin, DESI, and Gaia. 

## License

Educational use only.
