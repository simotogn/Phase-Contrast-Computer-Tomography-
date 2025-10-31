**2D Sinogram Generation — Absorption & Phase-Contrast (PBI)**

**Overview**

This project demonstrates how to generate 2D sinograms from test images (e.g., the Shepp–Logan phantom) to simulate X-ray tomography data.
It supports two acquisition modes:

* **Absorption:** standard simulation based on beam attenuation.
* **Phase Contrast (PBI):** simplified simulation of propagation-based phase contrast for X-ray imaging.

**Dependencies**
Install the required Python packages:

```bash
pip install numpy matplotlib scikit-image scipy
```

**Usage**

Open the notebook:

```bash
jupyter notebook ct.ipynb
```

Run all cells to:

* Generate the 2D phantom
* Compute the absorption sinogram
* Compute the PBI sinogram (including phase or gradient terms)
* Visualize results and compare differences

**Code Structure**

| Section | Description                            |
| ------- | -------------------------------------- |
| Setup   | Import libraries and define parameters |
| Phantom | Create synthetic phantom image         |
| Radon   | Compute absorption sinogram            |
| PBI     | Extend to phase-contrast sinogram      |
| Plot    | Visualize sinograms and images         |

**Output**

The notebook displays:

* Original phantom
* Absorption sinogram
* Phase-contrast sinogram (PBI)
