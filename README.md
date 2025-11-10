# [RECOMB'26] PC-POCS Sampler to reconstruct a sparse-view computer tomography image with both prior and measurements
A Predictor-Corrector based Projection Onto Convex Set Diffusion Sampler, used to reconstruct a sparse-view computer tomography image.
![PCPOCSSampler](./MedicalDiffusion.jpg)

## Requirements
1. Clone this repository
```bash
git clone https://github.com/yuanbingyan/PCPOCSSampler.git
```
2. Install Package: Create Conda environment
```bash
conda env create -f environment.yml
conda activate sip_torch
```
3. Prepare data. Download the LDCT-and-Projection-data | Low Dose CT Image and Projection Data from the official datasets: American Cancer Imaging Archive.
4. Now we are in the main path. Create a new path called samples, and create a new path again under the directory ./samples. Put the downloaded dataset in this path.
5. Run the script in terminal
```bash
python run_CT_recon.py
```
