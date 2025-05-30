# Downwelling irradiance model

The notebooks present the implementation of a downwelling irradiance model considering atmospheric conditions and clear sky.

### Dependencies

Make sure you have all required libraries. To get them, follow the instructions according to the type of environment that you are using.

#### Local environment

All dependencies are listed in the file `environment.yml`. I recommend you to recreate the Conda environment that I used. For that, you may follow some steps:
1. Install Miniconda on your computer (instructions can be found [here](https://www.anaconda.com/docs/getting-started/miniconda/install#quickstart-install-instructions)).
2. Open the Anaconda Prompt and navigate to the folder where the file was saved using `cd path/to/your/folder`.
3. The default environment name is irrad_model, but you can change it by editing the first line of the `environment.yml`. Then, create the Conda environment with the command `conda env create -f environment.yml`.
4. Activate the environment using `conda activate irrad_model` (or the name you used).
5. Open the Jupyter Lab by executing `jupyter lab`.
6. Navigate to find and open the notebooks.
7. Have fun.

#### Cloud environment

If you're working in a cloud server such as the [Copernicus JupyterLab environment](https://dataspace.copernicus.eu/analyse/jupyterlab), you may run the following command in a notebook cell to get the required dependencies: `!pip install earthengine-api seaborn pvlib geemap`

### Test data

You can find two CSV files in the repository:
- `Es_satlantic_alcatrazes_20231221.csv`: downwelling irradiance acquired by Seatlantic spectroradiometers in the region of Alcatrazes Archipelago on 21 Dec 2023.
- `Es_trios_canal_20250114.csv`: downwelling irradiance acquired by TriOS spectroradiometers in the region of the São Sebastião Channel on 14 Jan 2025.