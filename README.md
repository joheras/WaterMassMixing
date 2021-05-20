# Water Mass Mixing

Supplementary materials of the paper "Application of multi regression machine learning algorithms to resolve oceanic water mass mixing"

The description of each of the files is the following:
* README.md: This file.
* AtlanticOceanDatabase_clean.csv: Contains the data of the water samples used in (Romera-Castillo et al., 2019) together with the results of the OMP analysis in that paper.
* Water masses-IndependentLocations.ipynb: Jupyter notebook with all the instructions to run ML models on water samples. Used to train and evaluate different models in order to solve the water mixing problem.
* test.csv: Test set used to validate the model in the paper.
* train.csv: Train set used to validate the model in the paper.
* Folder Pure Water Masses:
  * AAIW.csv to WW.csv (15 files): Water samples from GlodapV2 database that match the properties (salinity, temperature and location) indicated for each of the source water types in the paper.
  * test.csv: The test set consisting only of water samples from (Romera-Castillo et al., 2019)
  * train.csv: The train set consisting only of water samples from (Romera-Castillo et al., 2019)
  * testPuras.csv: The test set consisting of samples form GlodapV2 database corresponding to the source water masses considered in the paper.
  * trainPuras.csv: The train set consisting of samples form GlodapV2 database corresponding to the source water masses considered in the paper.
  * testCombined: The test set consisting of sam,ples from both sources (Romera-Castillo et al., 2019) and GlodapV2.
  * trainCombined: The train set consisting of sam,ples from both sources (Romera-Castillo et al., 2019) and GlodapV2.
