# Extracting meaningful representaions from OpenAI's Jukebox
This repository collects code snippets that generate figures and results from my Bachelor of Science's final dissertation.

To reproduce results from the thesis, it is first necessary to extract song representations through https://github.com/p-lambda/jukemir.

Notebooks should then be used in the following order:
1. (optional) flatten_data_structure
  - if your files are in a hierarchichal file system structure, use this utility to flatten them into a single csv.
  - more information on the notebook     
2. Data cleaning / manipulation
  1. spot_duplicates
  2. filter
  3. pca
3. Model training and tuning 
  1. sweeps
     - uses WandB's sweep functionality to explore hyperparameter spaces for a shallow Neural Network
  2. best_model_training

Feel free to contact me for further information, or just to say hi :)
