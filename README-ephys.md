# **Extracellular electrophysiology processing**

## Steps for running (manual):

    1. Experimenter should complete input.xlsx spreadsheet with relevant information about experiment
    2. Electrode measurements e.g. Intan should be provided as separate Excel workbook e.g. electrode_mappings.xlsx but location referenced in 'electrode_recordings' column. (WIP)

Note: You will need input.xlsx for electrophysiology experiments (sample in root directory) for inclusion of raw data

## Files

---

- ephys_process3.ipynb (Main Notebook for reading and processing ephys files -> reads input.xlsx and electrode_mappings.xlsx; generates NWB output files)
    - For Intan format, uses ConvertIntanToNWB.py and WriteNWB.py 
- nwb_utils.ipynb 
    - code to generate electrode_mappings.xlsx file from source files
    - code to validate NWB files after generation