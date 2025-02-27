# TESS Time Correction

This repository shows how the TESS Quick-Look Pipeline applies barycentric time correction to time stamps recorded on the TESS spacecraft using spacecraft position and sky coordinates. It includes both the [data files](ephemeris-data/) containing the spacecraft position data (2018-2025) and a reference implementation with example usage in the ["TESS Time Correction" notebook](TESS Time Correction.ipynb).

To run the notebook, make sure you have Python installed on your system and create and activate a virtual environment (or skip this step if you prefer to use the global installation):
```shell
python3 -m venv .venv
source .venv/bin/activate
```
Then install the dependencies and start JupyterLab:
```shell
pip install -r requirements.txt
jupyter lab
```
Finally, in the browser window that opens, select the folder icon in the sidebar to open a file browser and select "TESS Time Correction.ipynb" to view and run the example notebook.
