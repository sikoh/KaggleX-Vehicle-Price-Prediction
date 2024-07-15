# KaggleX-Vehicle-Price-Prediction


**Description**<br>
The skill assessment challenge is a component of the application and will allow the program team to validate your hands-on experience in data science. Please note that the program team will review both your application responses and your skill assessment to determine the status of your application.
<br>
<br>
**Leaderboard**<br>
The leaderboard for this skill assessment challenge is not a reflection of your application standing and does not determine your acceptance.
<br>
<br>
**Evaluation**<br>
Root Mean Squared Error (RMSE)
Submissions are scored on the root mean squared error. RMSE is defined as:
<br>
<br>
RMSE=(1𝑁∑𝑖=1𝑁(𝑦𝑖−𝑦ˆ𝑖)2)12
<br>

where 𝑦ˆ𝑖
 is the predicted value and 𝑦𝑖
 is the original value for each instance 𝑖
.
<br>
<br>
**Submission File**<br>
For each id in the test set, you must predict the price of the car. The file should contain a header and have the following format:
<br>
<br>
id,price<br>
54273,39218.443<br>
54274,39218.443<br>
54275,39218.443<br>
etc.<br>

www.kaggle.com/competitions/kagglex-cohort4/overview/evaluation


---------------------------------------------------------------------------------------------

Led the Vehicle Price Prediction project, leveraging Python libraries such as Pandas, Scikit-learn, XGBoost, and
TensorFlow to process data, engineer features, and build predictive models. My approach involved identifying
outliers in datasets ('train.csv' and 'test.csv') using statistical methods like Interquartile Range (IQR). I applied
filtering techniques to remove outliers, ensuring our models were trained on reliable data points, which improved
their accuracy and reliability.
<br>
By extracting key features like engine power and car age, I optimized datasets for better predictive performance.
Utilizing advanced techniques such as One-Hot Encoding for categorical variables and StandardScaler for
numerical features, I standardized data to enhance model precision.
<br>
Implementing K-fold cross-validation with XGBoost allowed me to fine-tune model parameters effectively,
resulting in significant improvements in model performance. Evaluation using metrics like Mean Squared Error
(MSE) and R2 Score demonstrated the effectiveness of our approach, achieving an MSE of approximately 122.3
million and an R2 Score of 0.67 on validation data.
<br>
This project showcased my ability to manage data intricacies, ensuring robust model training and validation. It
highlighted my proficiency in feature engineering and advanced machine learning techniques, contributing to
accurate vehicle price predictions.
