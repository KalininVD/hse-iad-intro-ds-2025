# All homeworks for the 1st semester of Machine Learning course ([HSE iad-intro-ds 2025](https://github.com/hse-ds/iad-intro-ds/tree/master/2025))

This repository contains all the homeworks for the 1st semester of the Machine Learning course at HSE University, 2025. All homeworks are completed in Jupyter notebooks and are designed to be run in a Python environment. **All 8 homeworks** were graded by the course staff and **received full marks** (**including all bonus points** for the 5th and 7th homeworks).

## Reproduce locally

First, clone the repository:

```bash
git clone https://github.com/KalininVD/hse-iad-intro-ds-2025 homeworks
cd homeworks
```

Then, create a virtual environment and activate it:

```bash
python -m venv venv
venv\scripts\activate  # `source venv/bin/activate` on Linux or macOS
```

Next, install the required packages (listed in `requirements.txt`):

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

> [!Note] 
> `requirements.txt` includes all necessary packages with corresponding versions tested with Python 3.12 on Windows 11. In case of problems with future versions of packages or other Python versions, you can try manually installing other versions of the packages listed in the file.

Finally, you can open any Jupyter notebook (`.ipynb` file) in preferred IDE and run all the cells (choose the kernel corresponding to the created virtual environment).

Alternatively, you can start Jupyter Notebook server directly from the command line:

```bash
jupyter notebook
```

Then you can open the notebooks in your web browser (usually the `localhost` link opens automatically in your default browser).