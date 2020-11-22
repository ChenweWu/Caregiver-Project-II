Part 2 is to build 6 distinct predictive models for 6 outcome variables, cgdistress,cggad7,cgphq2,AGG_PHYS,AGG_MENT,SF12TOTAL

Data:
raw data is cgfinal414.csv
correctrf.csv is the results from random forest grid search in cgdistress variable, used for 3d visualization 
showcase

Models:
AGG_PHYS_final.ipynb contains model for AGG_PHYS
cdgistress_final.ipynb contains model for cgdistress
cggad7_final.ipynb contains model for cggad7
aggmental_final.ipynb contains model for AGG_MENT
cgphq_final.ipynb contains model for cgphq2
sf12_total_final.ipynb contains model for sf12total

LIME and 3D visualizations:
cgphq_LIME(SVM Only)_final.ipynb showcases use of LIME on SVM model with example of Cgphq classification
grid_search_3d_final.ipynb contains 3d visualization for the grid search

Workbook:
Tableau workbook is Tableau Workbook.twb
Corresponding data file for Tableau workbook is cgfinal414.csv

Models and Workbook and LIME uses raw data, while 3D visualizations use correctrf.csv