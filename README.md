## Kaggle Competition

# This repo holds all my code for the Kaggle competition.

1. Grupo Bimbo Inventory Demand
  - Data is relatively large, must set dtype in panda dataframe to save space.
  - Use incermental learning or online learing.
  - how to fill in the missing data?
  

##How to install XGBoost!!!!

Okay being honest, the first major obstale for becoming an Kaggle competition winner is installing XGBoost on windows!!!!!

on Mac and Linux, it is literally just one line: pip install xgboost! but pip install is disabled for windows!!!!

Okay, After spending one day trying all solutions on the web, this is the only one that works, just do exactly following:

1. Download Visual studio community 2013 (Must be 2013!!!!!!!This could take about 30 mins depends on ur network).
2. Create a folder anywhere. ex. C:\Users\xians\Desktop\xgboost
3. cd C:\Users\xians\Desktop\xgboost
4. git clone https://github.com/dmlc/xgboost/tree/v0.40 
5. go to C:\Users\xians\Desktop\xgboost\windows
6. Open the .sln file with visual studio 2013
7. This might prompt you to update libraries, click on “Yes”
8. Click on “Debug” dropdown menu and select “Release” instead
9. Click on “Win32” dropdown menu and select “x64” instead
10. Click on “Build” and select “Build Solution”
11. This will create the required files for xgboost installation
Open a command prompt
12. cd to Xgboost\wrapper folder
13. Type "python setup.py install"

Fucking done!!!!!! OKay, now FTW!!!!