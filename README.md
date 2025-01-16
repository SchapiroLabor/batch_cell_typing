# batch_cell_typing
Analyze the effects of intensity batch correction algorithms on cell typing models (MAPS &amp; XGBoost)


# Steps to reproduce
1. Git pull the MAPS repo + Install related dependencies
2. Replace the trainer.py script in MAPS/maps/cell_phenotyping/trainer.py with the script in this repo
    - This script only changes the input for the model.fit function to take in dataframes instead of a path
    - Implemented just for ease of use and batch running
3. Run maps_main.ipynb
