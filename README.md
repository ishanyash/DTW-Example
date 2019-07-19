# DTW-Example
Example of DTW algorithm's working.
The Code is written to find the accuracy of the respective dataset(s) with
different classification techniques. The Datasets we used were from UCR Timeseries
datasets.

To run the code you must:

install the following libraries:
1. tslearn
2. tqdm
3. sklearn
4. pyts
5. xgboost 

after installing them, 

1. You must mention the path of the folder where all the datasets are stored as downloaded
from the UCR timeseries site. (eg. here the PATH was "G:/Coding/ML/UCRArchive_2018/" )
2. Make a list of datasets which you want to operate on, and name the list as 'dataset_list'.
The names of the datasets must be exactly filled, as they are case sensitive.
3. Similarly the window size, warping window, word size, number of bins list must be made.
4. To extract the accuracies as a matrix, we have made a list named 'ALL' where all the
accuracies will be stored according to the name of datasets and its classsification technique.
5. After obtaining the results, we export it as csv file.
6.Further we used matplotlib for further analysis and comparisons between the clasification 
techniques.
