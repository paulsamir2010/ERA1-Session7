# ERA1-Session7
 ERA1-Session7
 
## Target of this Assignment
99.4% 
Less than or equal to 15 Epochs
Less than 8000 Parameters
Do this using your modular code. Every model that you make must be there in the model.py file as Net1, Net2 etc.

### Target , Results and Analysis of systematic iterations 

#### 1)	Setup and skeleton

File = Structure_and_Skeleton.ipynb

Target:
1.	Get the set-up right
2.	Set Transforms
3.	Set Data Loader
4.	Set Basic Working Code
5.	Set Basic Training  & Test Loop

Results:
1.	Parameters: 25,104
2.	Best Training Accuracy: 99.23%
3.	Best Test Accuracy: 98.88%

Analysis:
No of Parameters are more
Test Accuracy is low
Model is over-fitting.

#### 2a) Model with Less Parameters + Batch Normalization 

Add Batch-norm to increase model efficiency.
File = Lighter_model_with_Batch_Norm.pynb

Target:
1.	Add Batch-norm to increase model efficiency.
2.	Reduce the number of parameters (below 8000)
   
Results:
Parameters: 7,956
Best Training Accuracy: 99.4 %
Best Test Accuracy: 99.14 %

Analysis:
Train accuracy achieved 99.4%
Model is over-fitting, but we are changing our model in the next step
 	Test Accuracy increased to 99.14 % but below target 99.4%
Parameters 7,956 are less than target of 8000


#### 2b) Add Dropout for reducing overfitting to above model

File = With_Dropout_added.ipynb

Target:
•	Reduce the overfitting by using Dropout

Results:
Parameters: 7,956
Best Training Accuracy: 99.48 % (epoch 13)
Best Test Accuracy: 99.16 % (epoch 13)

Analysis:
Model is still Overfitting 
	Test Accuracy marginally increased to 99.16 with 7,956 parameters


#### 3) Add Image Augmentation to above model

File =  With_Image_Augmentation.ipynb
Target:
•	Improve the Test accuracy from 99.1% to target 99.4%
•	Add Image Augmentation to make training harder and reduce overfitting

Results:
•	Parameters: 7,956
•	Best Training Accuracy: 99.18%
•	Best Test Accuracy: 99.32% (epoch 8)

Analysis:
•	Model is not overfitting. 
•	Test Accuracy improved to 99.32% from 99.16%
•	However, Test accuracy stays at 99.32 . may be little more capacity is to be added



