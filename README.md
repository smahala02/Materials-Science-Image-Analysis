# Image Analysis for Materials Science

This repository contains image analysis data for materials science, focusing on particle diameter measurement and image scaling. It includes Python scripts, image files, and results related to the analysis of particle size and distribution in materials. The key focus is on analyzing the particle equivalent diameters and utilizing scalebars for accurate measurement.

## Table of Contents

1. [Introduction](#introduction)
2. [Particle Diameter Analysis](#particle-diameter-analysis)
3. [Scalebar and Image Calibration](#scalebar-and-image-calibration)
4. [Files in the Repository](#files-in-the-repository)
5. [Getting Started](#getting-started)
6. [Installation](#installation)
7. [Contributing](#contributing)
8. [License](#license)

---

## Introduction

This repository is dedicated to the **image analysis** of materials science data. It covers key concepts such as:
- **Particle diameter measurement**: Using image analysis techniques to determine the size and distribution of particles in a material.
- **Scalebar calibration**: Applying scale bars to images for accurate spatial measurements.

The data has been generated from real experiments and is analyzed using Python scripts and image processing techniques.

## Particle Diameter Analysis

The particle diameter analysis focuses on measuring the equivalent diameters of particles from images and calculating their distribution. The data provided in `diameter.txt` contains the equivalent diameters for multiple particles.

Here is an excerpt from `diameter.txt`:
```
# Particle  --  Equivalent diameter
1.000000-----------39.493271
2.000000-----------98.019720
6.000000-----------26.986905
14.000000-----------4.068429
...
```
Explore the full data here: [diameter.txt](./diameter.txt).

## Scalebar and Image Calibration

The repository also contains images used for calibration, including a **scalebar** which provides a reference length of **1 µm**.

![Scalebar](./scalebar.png)

This scalebar is used to scale images and accurately measure particle sizes. The image `Coarse_250kx.TIF` is an example of an analyzed image file.

## Files in the Repository

- **`diameter.txt`**: Contains particle equivalent diameter data.
- **`scalebar.png`**: An image of a scalebar used for calibration.
- **`Coarse_250kx.TIF`**: An image file used for analyzing particles at 250,000x magnification.
- **`Image Analysis for Materials Science.ipynb`**: A Jupyter notebook that contains Python code for analyzing the images and calculating particle diameters.

## Getting Started

### Prerequisites

You will need the following software and libraries to run the analyses and visualizations:
- Python 3.x
- NumPy for numerical data processing
- Matplotlib for visualizing results
- PIL (Python Imaging Library) for image processing
- Jupyter Notebook (optional, for interactive analysis)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/smahala02/Materials-Science-Image-Analysis.git
   ```

2. Install the required Python libraries:

   ```bash
   pip install numpy matplotlib pillow
   ```

3. (Optional) Open the Jupyter notebook for interactive analysis:

   ```bash
   jupyter notebook 'Image Analysis for Materials Science.ipynb'
   ```

## Contributing

Contributions are welcome! If you have ideas to improve the image analysis or add new techniques, feel free to submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b new-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin new-feature`).
5. Open a pull request.

## License

This repository is licensed under the MIT License. See the `LICENSE` file for more details.

