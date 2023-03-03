# README 

This problem and dataset was found at: https://archive.ics.uci.edu/ml/datasets/Statlog+%28Shuttle%29

The problem was solved by building a neural network from scratch using python, learning from the following book...

Title: "Neural Networks from Scratch in Python"
Authors: Harrison Kinsley & Daniel Kukieła
Publisher: Harrison Kinsley, 2020

----------------------------------------------------------------------------------------------------

Description of SHUTTLE Dataset (STATLOG VERSION)

THIS DATASET SHOULD BE TACKLED BY TRAIN/TEST.

NUMBER OF EXAMPLES
	training set     43500
	test set         14500
NUMBER OF ATTRIBUTES
	9

The shuttle dataset contains 9 attributes all of which are numerical.
The first one being time.  The last column is the class which has been 
coded as follows :
        1       Rad Flow
        2       Fpv Close
        3       Fpv Open
        4       High
        5       Bypass
        6       Bpv Close
        7       Bpv Open
        
Approximately 80% of the data belongs to class 1. Therefore the default 
accuracy is about 80%. The aim here is to obtain an accuracy of 
99 - 99.9%.        

Validation set:
The examples in the original dataset were in time order, and this time order
could presumably be relevant in classification. However, this was not deemed
relevant for StatLog purposes, so the order of the examples
 in the original dataset was randomised, and 
a portion of the original dataset removed for validation purposes.

Acknowledgment:
Thanks to Jason Catlett of Basser Department of Computer Science, 
University of Sydney, N.S.W., Australia for providing the shuttle dataset.  
Thanks also to NASA for allowing us to use the shuttle datasets.
        
