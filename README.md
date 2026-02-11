
# tutorial-DiemPy

**Tutorial for polarizing genomes using the Python implementation of the diem algorithm.**

This repository provides a step-by-step workflow and example data for using the `diemPy` module to polarize genomic SNP data. It is intended as a practical guide and primary documentation for new users.


## How to Access and Use This Tutorial

Users do NOT need to use git to access this tutorial. Please follow the method that best fits your experience:

### Option 1: Download the Entire Repository as a ZIP

This is the simplest and safest way to get started. You do not need git for this method.

1. On the [main repository page](https://github.com/DerekSetter/tutorial-DiemPy), click the green **Code** button.
2. Select **Download ZIP**.
3. Extract the ZIP file and navigate to the  `example_workflow` folder.


### Option 2: For Advanced Users — Using Git

If you are familiar with git and want to use version control:

1. **Do NOT work directly in the main repository.**
2. Fork this repository to your own GitHub account (click the **Fork** button at the top right of the GitHub page).
3. Clone your fork to your local machine:
	```bash
	git clone https://github.com/your-username/tutorial-DiemPy.git
	cd tutorial-DiemPy/example_workflow
	```
4. Work in your own fork. Do not push changes to the original repository.

If you have already cloned the main repository and want to prevent accidental pushes, you can remove the push URL:
```bash
git remote set-url --push origin no_push
```

---

## Next Steps: Running the Tutorial

1. Install `diemPy` by following the [official installation instructions](https://diempy.readthedocs.io/en/latest/intro.html).
2. After installation, activate your `diempy` conda environment:
	```bash
	conda activate diempy
	```
3. In a terminal, navigate to the `example_workflow` directory and start Jupyter Lab. It will open in your default browser:
	```bash
	jupyter lab
	```
4. Open `tutorial.ipynb` in your browser and follow the instructions.

## Repository Structure

- `example_workflow/tutorial.ipynb` — Main tutorial notebook with step-by-step instructions.
- `example_workflow/data/` — Example input data as VCF file.
- `example_workflow/user_files/` — User-provided files for data-specific workflow customization:
	- `individuals_masked.txt`
	- `iphiclides_ploidy_update.txt`
	- `relative_rec_rates.txt`
	- `sites_masked.bed`
	- `user_initial_pol.txt`
- `example_workflow/output/` — Output directory for results (initially empty).

## Usage

1. Follow the steps in `tutorial.ipynb` to process the example data.
2. The files in `user_files/` provide data-specific information to include in the analysis
3. Results will be saved in the `output/` directory.





## Support

For questions or issues, please first refer to the [diemPy documentation](https://diempy.readthedocs.io/en/latest/).

If you have qustions or concerns about the tutorial, open an issue in the [tutorial-DiemPy repository](https://github.com/DerekSetter/tutorial-DiemPy/)

If you have issues relating to the `diempy` package itself, please open an issue in the main [diemPy repository](https://github.com/Studenecivb/diemPy).

