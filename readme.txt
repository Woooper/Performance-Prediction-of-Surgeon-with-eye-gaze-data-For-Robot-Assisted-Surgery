Istanbul Technical University - Biomedical Engineering - Fundamental of Biomedical Informatics Final Project

Developed by
• Murat Teksin 

Robot assisted surgery (RAS) is quite new method in medicine. 
In order to get experience in RAS, da Vinci Skill Simulator (developed in collaboration with Mimic® Technologies, Inc. Seattle, WA, USA) is used. 
Simulation system has 27 different session to get experience with RAS. 
Sessions starts with some basic pick and drop applications and ends with cutting vessels, isolation and bleed control. 
System gives score end of sessions tracking some parameter like instrument travel, blood loss, broken vessels etc. 
However, system can’t be used in real life operations as scoring and it is needed to score with different measurement from the RAS operator. 
Therefore, EEG and Eye-Tracker data collection. 
Also, participant demographic data Eye tracker and EEG are non-invasive methods to collect data from the subjects and both of them gives information about the subjects’ 
cognitive situation and stress level which affect the performance of the participant. Unfortunately, EEG data can be complicated to extract features. 



Goal of the project:

Score prediction from eye-gaze and participants’ demographic data.

Data Set:

Eye-gaze dataset remain in EYE/EYE folder as csv files. There are total 1559 eye-gaze data.
csv files has 20 columns that are 1) Gaze point X, 2) Gaze point Y, 3) Gaze point 3D X, 
4) Gaze point 3D Y, 5) Gaze point 3D Z, 6) Gaze direction left X, 7) Gaze direction left Y, 
8) Gaze direction left Z, 9) Gaze direction right X, 10) Gaze direction right Y, 11) Gaze direction right Z, 
12) Pupil position left X, 13) Pupil position left Y, 14) Pupil position left Z, 15) Pupil position right X, 
16) Pupil position right Y, 17) Pupil position right Z, 18) Pupil diameter left, 19) Pupil diameter right, 
20) Eye movement type index (1: Fixation; 2: Saccade; 0: Unknown).

Demographic data ramin in EYE folder as "PerformanceScores"
1) EEG File Name, 2) Eye File Name, 3) Subject ID, 4) Gender (F: Female, M: Male), 
5) Age (year), 6) Dominant Hand, 7) Task ID, 8) Try, 8) Performance (out of 100).


Used environment:
Jupyter Lab - Python 3.7.6

Using Freworks:
numpy
pandas
seaborn
matplotlib
sklearn
arch
xgboost
tensorflow

Useful links:
https://physionet.org/content/eeg-eye-gaze-data/1.0.0/#files
https://medium.com/analytics-vidhya/exploratory-data-analysis-eda-cbfc0b0e4922
https://medium.com/@thedatabeast/xg-boost-model-development-to-deployment-a7a89cae05a5
https://datascience.stackexchange.com/questions/18414/are-there-any-rules-for-choosing-the-size-of-a-mini-batch
https://writter3.medium.com/what-is-regression-3a99761332a
https://medium.com/codex/minmaxscaler-in-4-minutes-how-it-gets-its-values-f545361a586a
https://stats.stackexchange.com/questions/164876/what-is-the-trade-off-between-batch-size-and-number-of-iterations-to-train-a-neu
https://mull-overthing.com/what-is-alpha-and-beta-in-garch/
https://barnesanalytics.com/garch-models-in-python/#google_vignette
https://drveri.medium.com/loss-functions-in-keras-python-for-deep-learning-c2e4b1bcdfec
