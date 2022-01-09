# ApplicationCategoryPrediction
A repository for predicting appstore category of mobile applications using their description text.

## Dataset
The dataset is provided by CafeBazaar [link](cafebazaar.com) at a contest held by the team.

### Details
The dataset contains 37899 train and 10000 test samples, respectively. Each training sample has the following set of columns:
 - app_id
 - description_fa
 - label

Samples in the testset do not have labels since it was a contest. If you're looking for the labels, you should ask the organizing team since, they didn't provide the labels after the contest.

## Method
A pretrained bert on persian corpus was used. The pretrained model was taken from [Hooshvarelab/ParsBERT](https://github.com/hooshvare/parsbert).

## Results
I achieved 75.2 % test accuracy which ranked 10 amogst 125 valid submission. The highest score in the leaderboard was 76.3 %.


Happy Coding!

Taha.
