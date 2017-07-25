# Instruction to run 
## Part 2
1. Run train_parmas.py to train the data, transition and emition parameters will be stored in /params folder
2. Run Part2.py to generate dev.p2.out for all language

## Part 3
1. Run train_params.py ( if you already did this in part 2, no need to do it again, since it uses the same parameters for predictoin)
2. Run Part3.py to generate dev.p3.out for all language

## Part 4
1. Run train_params.py ( if you already did this in part 2 or 3, no need to do it again, since it uses the same parameters for predictoin)
2. Run Part3.py to generate dev.p4.out for all language

## Part 5
Just run Part5_perceptron.py and test.p5.out will be generated for EN and ES

Ensure the parameter are:

ITER = 80

TOP_train = 1

TOP_predict = 1

CLEAN_DATA = False

For dev data, set TEST = False

For set data, set TEST = True


Detailed implementation can be found on 
https://github.com/hellozhanghao/ML_Project.git


