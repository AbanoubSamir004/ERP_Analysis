# ERP_Analysis

This repository contains code for an ERP analysis of random time data with 2 classes and 50 trials per class. The code includes various steps for processing the data, such as:

- Epoching: The continuous data is segmented into smaller time windows, known as "epochs," that correspond to specific events or stimuli in the study.

- Baseline correction: This step is to account for variations in the signal that occur independently of the specific event or stimulus of interest. A common method is to subtract the mean voltage of a prestimulus period from all voltage values in the epoch.

- Averaging: Multiple trials of the same event or stimulus are combined to increase the signal-to-noise ratio of the data.

- Artifact rejection: Any remaining artifacts that were not removed during preprocessing are identified and excluded.

- Data visualization: Plots or images are created to depict the average voltage across time and electrodes.

