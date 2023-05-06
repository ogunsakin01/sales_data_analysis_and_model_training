# Experiment Setup

Before doing anything else, ensure `python` and its associated terminal helper command `pip` is installed and working on your computer. You can confirm that by running this command in the terminal

```shell
python3 --version && pip3 --version
```

or run the command below to confirm another version of `python` and `pip` is installed

```shell
python --verson && pip --version
```

If Python is installed and working, then you can proceed to the next step by installing the required libraries and packages using in this research experiment. You can do that by running the command below

```shell
pip3 install --trusted-host pypi.python.org -r requirements.txt
```

This command will install the following libraries and packages to your computer
`flask`, `numpy`, `pandas`, `jupyter`, `scikit-learn`, `keras`, and `folium`

## Accessing the Jupyter notebook

To access the main experiment, run the command below in your terminal while still in the root folder of the project.

```shell
jupyter notebook sales_analysis_experiment.ipynb
```
