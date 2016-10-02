## Kaggle Competition

# This repo holds some of my code for the Kaggle competition.

1. Grupo Bimbo Inventory Demand
  - Data is relatively large, must set dtype in panda dataframe to save space.
  - Use incermental learning or online learing.
  - how to fill in the missing data?
  

##How to install XGBoost!!!!

Okay being honest, the first major obstale for becoming an Kaggle competition winner is installing XGBoost on windows!!!!!

on Mac and Linux, it is literally just one line: pip install xgboost! but pip install is disabled for windows!!!!

Okay, After spending one day trying all solutions on the web, this is the only one that works, just do exactly following:

1. Download Visual studio community 2013 (Must be 2013!!!!!!!This could take about 30 mins depends on ur network).
2. Install Git
3. Create a folder anywhere. ex. C:\Users\xians\Desktop\xgboost
4. Open Git
5. cd C:\Users\xians\Desktop\xgboost
6. git clone https://github.com/dmlc/xgboost/tree/v0.40 
7. go to C:\Users\xians\Desktop\xgboost\windows
8. Open the .sln file with visual studio 2013
9. This might prompt you to update libraries, click on “Yes”
10. Click on “Debug” dropdown menu and select “Release” instead
11. Click on “Win32” dropdown menu and select “x64” instead
12. Click on “Build” and select “Build Solution”
13. This will create the required files for xgboost installation
Open a command prompt
14. cd to Xgboost\wrapper folder
15. Type "python setup.py install"

Fucking done!!!!!! Okay, now let's conquer Kaggle together!!!!!!!!

Reference: https://datanoord.com/2016/02/06/setup-xgboost-on-windows-python/

# Adding XGBoost model
