LACAM:

For executing experiments firstly setup environment with the main branch - setup needs folder

Benchmark codes in lacam-benchmark branch. For execute experiment:

-- cd algorithms
-- python3 eval.py

Optimized codes in lacam-optimized branch. For execute experiment:

-- cd algorithms
-- python3 eval.py


NOTES:
- Only change codes in pibt.cpp and sipp.cpp

DCC:

Our work on DCC can be found in the dcc folder under main, specifically in the files dccmethodone.ipynb and dccmethodtwo.ipynb. 
Both notebooks use the dataset located in the test_set folder within dcc. While dccmethodone.ipynb uses the model 1.pth from the saved_models directory, dccmethodtwo.ipynb uses 128000.pth from the same directory. 
If you want to run the original version of DCC, you need to set it up through the DCC module located inside the algorithms folder in main.
