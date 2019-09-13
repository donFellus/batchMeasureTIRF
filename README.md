# batchMeasureTIRF
This macro is designed to automatically segment, subtract background and measure standard parameters (based on the Analyze -> Set Measurements settings in ImageJ) from .vsi (can be modified to accommodate any filetype) files acquired by TIRF microscopy, and store the images as .tiff files in subfolders in a destination folder.

The macro first prompts you to select the parent folder of the raw TIRF data. Then you are prompted to select a reference file from the raw data to denote the various channels. Choose the first .vsi file in the raw data folder. Finally you are prompted to select a parent output folder in which you want to save the segmented .tiff files.

The reference file will then automatically open along with a dialog box. Fill in the channel names in the correct order (according to the reference file). The SIRC/IRM channel must be denoted SIRC. The rest of the channels you are free to call whatever you want. The macro will then analyse and save the images accordingly.
