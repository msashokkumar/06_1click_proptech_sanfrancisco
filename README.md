# 06_1click_proptech_sanfrancisco

This jupyter notebook offers insights into potential buying properties and then rent them in San Francisco. The notebook takes gross rent and sale price per square foot statistics to determine and suggest districts to invest in.

## Technologies

This protech analyzer is a Jupyter notebook built with the following technologies:

### Language

| Language | Version |
|----------|---------|
| Python   | 3.7.11  |

### Libraries and Frameworks

| Component | Version |
|-----------|---------|
| Anaconda  | 1.9.0   |
| Conda     | 4.11.0  |
| Jupyter   | 3.2.1   |

### Operating System

This version of the software is operating system agnostic.

---
## Installation Guide

### Pre-requisites

- Python 3.7
- Anaconda 1.9.0
- Conda 4.11.0
- Jupyter 3.2.1
- A conda environment created specially for this project.


### Required Python Packages

- ipykernel
- hvplot
- pyviz
- panel
- geoviews

### Running the Analyzer

Install a new conda environment for this project. We will be using `python 3.7.11` for this repository.

```bash
conda create -n dev_proptech python=3.7.11 anaconda
```

Activate the newly created environment and verify the python version.

```bash
conda activate dev_proptech
python --version
```

Install and add the ipykernel environment to your jupyter notebook.

```bash
conda install -c anaconda ipykernel
python -m ipykernel install --user --name=dev_finplanner
```

Install the required python packages.

```bash
conda install ipykernel
conda install hvplot
conda install -c pyviz panel
conda install -c pyviz geoviews
```

Clone the remote repository to your local developer environment and `cd` into the folder.
```bash
git clone git@github.com:msashokkumar/06_1click_proptech_sanfrancisco.git
cd 06_1click_proptech_sanfrancisco
```

Start the jupyter lab server from the terminal as follows:

```bash
jupyter lab
```

Open and execute the file `06_1click_proptech_sanfrancisco/san_francisco_housing.ipynb`

---
## Contributors

```markdown
{
  "name": "Ashok Kumar Madhavi Selvaraj",
  "email": "ashok.ms.kumar@gmail.com",
  "linkedin": "https://www.linkedin.com/in/msashokkumar"
}
```
---

## License

Please refer to LICENSE.