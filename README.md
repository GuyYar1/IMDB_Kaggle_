# IMDB_Kaggle_

Perform End-to-end for ML Model Creation

Each steps is a jupyter lab notebook:
  1. work towars flat File on first phase.
  2. work on EDA to observe and know the data for the ongoing massage.
  3. work on cleansing phase toward feature selection- regularization and optimization and (NLP) analysis techniques
  4. work on feature selection- regularization and optimization- Current.
  5. work on  Model Selection and Finetuning.

Environment:
  1. Dependency management and packaging in Python -poetry
  2. Python 3.10 / 3.11.
  3. ML libraries

version control:
 work with GitHub desktop on the different versions.
 it is important to mention that we have 3 type of files required versions.
   1. Data - csv or pkl. ( Initial data, flat file data, progress data along the progress of the notebooks above) - {customer update or update collections.}
   2. Code - the code is preserved and while developing we find issue that layter on fixed.  {CI\CD process} (Ver. 1.0 - 1.0.1 - 1.0.2 ....1.0 RC --> Ver 1.0 released)
   3. Models - models are version based too.  in development phase and later on on updating due to drifting.  {updated due to a change of Data or code}

    suggestion on production:
    data: code_<code_version>_data_<data_version> model:model_<model_version>_data_<data_version>_code_<code_version>
Products:
  1. Several models -PKL format.
  2. presentation file - PPT format.
  3. Overview Project - word format.
  4. lock from 3.10 and 3.11 kernel env. - poetry

     
The data came from Kaggel chalange:  https://www.kaggle.com/datasets/asaniczka/full-tmdb-tv-shows-dataset-2023-150k-shows
follows the best practice guidelines.

Note:
 1. i moved from 3.10 toward 3.11 so unsupported transition require to save it on excel file including json Dtype for auto loading.
  pkl libjob doesnt support it currently. 
