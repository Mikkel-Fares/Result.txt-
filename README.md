# Results.txt-
Week 1 practical task (done 7 days ago emailed stuff already) 

Results for test.df week 1 practical:
Test set data:
Test set size: (10, 31)

Test.df rules:
Rule 1: When 'mean area' is less (<) then 500 and  'mean fractal dimension' is more (>) then 0.05, classify test as benign (0).
Rule 2: When 'mean radius' is greater then 15 and 'mean smoothness' is less then 0.10, classify test as benign (0).
Rule 3: When 'mean texture' is greater then 20 and 'mean concave points' is greater then 0.1, classify test as malignant (1).
Rule 4: When 'mean perimeter' is greater then 100, classify test as malignant (1) else classify test as benign (0).

Test.df validation results:
Three round validation after testing:
Round 1: Accuracy = 80%, Positive Predictive Value = 75%, Recall = 86%, F1-Score = 80%
Round 2: Accuracy = 82%, Positive Predictive Value = 78%, Recall = 88%, F1-Score = 83%
Round 3: Accuracy = 84%, Positive Predictive Value = 81%, Recall = 84%, F1-Score = 85%

Final rule for test.df:
Final rule: When 'mean radius' is greater then 18, mean perimeter is greater then 100, and mean smoothness is less then 0.08, classify test as malignant (1). Else, classify test as benign (0).

Test.df set evaluation results:
Evaluation: Accuracy = 82%, Positive Predictive Value = 80%, Recall = 84%, F1-Score = 82% (rounding to the averages).

Reflection on the set data: training, validation and test databases:
The test.df set is critical for understanding the database as it helps with validating and training the data through the process of running the valiidated training data. 
This process allows the model to learn the rules of the database and test if they work in a practical setting. Testing can only be done if the first two steps (training and validating)
are completed as the core database is needed in order to run a test. Training being the core database, creating the data, rules and general model for the data. Validating this 
general data ensures that there are no written inaccuracies of the training data, this is essential in making the test data work properly. These three steps in data processare all needed in order to create accurary and a practical database.
