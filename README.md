# language_learning_cisco

Contains:
1. the code to run the pipeline
2. the datafiles for the cisco experiments provided (csv)
3. an example of running the pipeline with one of the cisto experiments (data11)

Setup:
Add the ciscoPL folder inside your main language_learning folder, and then also add another folder for your project, which contains the datafiles

In this repo I provide the following structure:
language_learing_repo
./ciscoML
./test1 (name of my working directory)
./test1/data
./test1/data/all the data files in csv format

To run:
Every file has comments on how to run the file, but it is mainly 
cd language_learing_repo

then
python ./ciscoPL/pythonfile proyectname experiment
example
python ./ciscoPL/1_Clusterer.py test1 data11

NOTES:
5_Learner.py produces a grammar file within the lang folder
6_Predictor.py and 7_FullPredictor.py use this grammar file but named dict.dict

After running 5_learner.py you must rename the grammar files to dict.dict
