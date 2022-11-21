# **Neurodata Without Borders (NWB) back-end conversion scripts**

***Scripts*** are useful in converting data from prorpritary formats into NWB format.  Scripts are expected to be used as back-end to U19 data sharing portals: ***usarhythms.ucsd.edu, highandlow.dk.ucsd.edu***

Currently supported experimental data is:
1. Widefield Imaging (meta-data only)
2. Extracellular electrophysiology (Intan -> NWB data conversion)
3. Calcium imaging (WIP)

## Steps for running (manual):

    1. Activate python virtual environment with required modules (nwb on my computer) *see requirements.txt for installed modules
    2. Open jupyter notebook corresponding to experiment type
    3. Edit constants (file paths at top file) and run

Note: You will need input.xlsx for electrophysiology experiments (sample coming) for inclusion of raw data


## Features

---

- Conversion for Intan format to NWB format
- Integration with back-end relational database (in progress)
- Ability to aggregate NWB containers (for uploading to NIH-approved respositories)

## Installation

---

1. create virtual environment in home directory (e.g. 'C:/Users/Duane/')
`python -m venv nwb`
2. Activate virtual environment
`C:/Users/Duane/nwb/Scripts/activate.ps1`
3. Install required modules
`pip install -r requirements.txt`

## Contribute

---

[Issue Tracker] (https://github.com/drinehart1/nwb/issues)

[Source Code] (https://github.com/drinehart1/nwb)

## Support

---

If you are having issues, please let me know.
Duane Rinehart
drinehart[at]ucsd.edu

## License

---
The project is licensed under the [MIT license](https://mit-license.org/).
