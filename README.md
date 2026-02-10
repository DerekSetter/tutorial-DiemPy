
# tutorial-DiemPy

**Tutorial for polarizing genomes using the Python implementation of the diem algorithm.**

This repository provides a step-by-step workflow and example data for using the `diemPy` module to polarize genomic SNP data. It is intended as a practical guide and primary documentation for new users.

## Getting Started

### 1. Install diemPy
Follow the installation instructions at the [diemPy documentation](https://diempy.readthedocs.io/en/latest/intro.html). The main repository is available at [Studenecivb/diemPy](https://github.com/Studenecivb/diemPy).

### 2. Clone this repository
Clone or download this repository to your local machine:

```bash
git clone https://github.com/DerekSetter/tutorial-DiemPy.git
cd tutorial-DiemPy/example_workflow
```

### 3. Set up your environment
Activate your `diempy` conda environment:

```bash
conda activate diempy
```

### 4. Launch Jupyter Lab
Start a Jupyter Lab session and open the tutorial notebook:

```bash
jupyter lab
```
Then open `tutorial.ipynb` in your browser.

## Repository Structure

- `example_workflow/tutorial.ipynb` — Main tutorial notebook with step-by-step instructions.
- `example_workflow/data/` — Example input data (e.g., VCF files).
- `example_workflow/user_files/` — User-editable files for workflow customization:
	- `individuals_masked.txt`
	- `iphiclides_ploidy_update.txt`
	- `relative_rec_rates.txt`
	- `sites_masked.bed`
	- `user_initial_pol.txt`
- `example_workflow/output/` — Output directory for results (initially empty).

## Usage

1. Follow the steps in `tutorial.ipynb` to process your data.
2. Edit files in `user_files/` as needed for your analysis.
3. Results will be saved in the `output/` directory.


## Preventing Accidental Pushes

To help keep the main repository clean and avoid accidental changes, please follow these guidelines:

- **Do not push changes directly to this repository.**
- If you want to experiment or save your work, fork this repository to your own GitHub account and push changes there.
- Alternatively, download the tutorial to your local machine directly rather than as a git repoistory. 
	

## Support

For questions or issues, please refer to the [diemPy documentation](https://diempy.readthedocs.io/en/latest/) or open an issue in the main [diemPy repository](https://github.com/Studenecivb/diemPy).

