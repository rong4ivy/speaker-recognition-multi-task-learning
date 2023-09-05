# multi-task learning
## Research Question 
### What is the difference between separate models and multi-tasks learning model? 
### which performs better for all the tasks? 
### what are their advantages and disadvantages ?

## Experiment Details

This experiment uses one dimensional 2 features to predict the dialect. The features are:
### mfcc(40),mel<br>

The features extraction function is as follows:
    
### features = extract_feature(wav_file, mfcc=True,  mel=True, nhop=nhop)
For more details, please refer to the feature_extract function. Donot be overwhelmed by the feature extraction function. The function is just a wrapper of all possible features that can be combined and explored. 



## Experiment Results 
### Separate models perfom better than multi-task learning for the same architecture and parameters. For the sake of fair comparsion, everything is same except that separate models train the MLP model separately for three tasks, while multi-task learning trained and predict the three tasks at the same time. 

- Rong Wang, 04.08,2023
