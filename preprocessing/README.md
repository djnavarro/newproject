
# Preprocessing

This folder should contain the preprocessing scripta. Each experiment should 
have one (and only one, ideally) `.R` file, named in the standard way. 
 If there is an experiment called "urntask", for instance, the 
corresponding preprocessing script should be called `preprocess_urntask.R`.

The preprocessing script should read data files from the raw data folder within the
relevant experiment (e.g., [./experiments/exp_urntask/data](./experiments/exp_urntask/data))
but should not write anything to that folder. The only thing it should do is
generate the clean data file, e.g. [./data/data_urntask.csv](./data/data_urntask.csv)
