**Machine Learning Challenge**
Objective of the problem: The objective of the problem is to predict values “Price” attribute from the given features of the Test data. The predictions are to be written to a CSV file along with ID which is the unique identifier for each tuple. Please view the sample submission file to understand how the submission file is to be written. Please upload the submission file to get a score. 

**Description of files:**

Training File: All features including the target would be present in this file. Machine learning model would trained using this file. This file is to be used for training and validation.
Test File: This file contains all features, but the target variable. Prediction is to be made for all tuples in the test file. The predicted values are to be written to a CSV file along with ID and uploaded.
Sample Submission: Sample submission is an example of how the actual submission file should be like

**Description of attributes:**

* Area(total): Total area of the plot.

* Nbedrooms: Number of bedroom in the house.

* Nwashrooms: Number of washroom in the house.

* Roof(Area): Total area of the terrace

* Lawn(Area): Area of the lawn including garden and parking

* Nfloor: Number of floors in the house

* API: Air purity index api is in percentage for example if api is 85 it means its 85% of the standard api for the city.

* ANB: Amenities near by amenities like hospital, park , multiplex , malls etc within 2 miles.

* Grade: grade is provided by government and it depends on the age and condition of the house. Higher the grade better the condition is.

* Price: current estimated price of the house as suggested by the company. 


**Evaluation Criteria:** Normalised root of MSE . All values would be normalised to 100. Any member of a team may make a submission and 15 submissions are allowed per team. All teams must submit their projects to the code submission stage.


**Evaluation Algorithm**

Root Mean Square Error (RMSE)

normalization_constant 100000