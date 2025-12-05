# SAT5141FinalProjectORCaseDuration
CDSS that intakes OR Scheduling Data and outputs Predicted Case Duration

Used kaggle data set: 
Falk, J. (2022). Operating Room Utilization. Kaggle. https://www.kaggle.com/datasets/thedevastator/optimizing-operating-room-utilization

Preprocessing included removing obsolete, redudant, and potential data leaking columns.
Screen data for O/null time values (potentially indicating case cancellations. 

CDSS evaluated by Linear Regressor, SVR, and GBR models.  

Based off R2 and MAE performance; SVR was superior model.

Work Cited:
B, Arunachalam. “How to Build a Linear Regression Model – Machine Learning Example.” freeCodeCamp.Org, freeCodeCamp.org, 6 Sept. 2023, www.freecodecamp.org/news/build-a-linear-regression-model-with-an-example/.
Falk, J. (2022). Operating Room Utilization. Kaggle. https://www.kaggle.com/datasets/thedevastator/optimizing-operating-room-utilization
Hembroff, Guy. “SAT5141 Disease Progression.” CAS, SAT5141, mtu.instructure.com/courses/1575642/pages/part-i-disease-progression-modeling-dpm. Accessed 20 Nov. 2025.
Saraswat, Manish. “Beginners Guide to Regression Analysis and Plot Interpretations Tutorials & Notes: Machine Learning.” HackerEarth, www.hackerearth.com/practice/machine-learning/machine-learning-algorithms/beginners-guide-regression-analysis-plot-interpretations/tutorial/. Accessed 5 Dec. 2025.
“Support Vector Regression (SVR) Using Linear and Non-Linear Kernels in Scikit Learn.” GeeksforGeeks, GeeksforGeeks, 6 Aug. 2025, www.geeksforgeeks.org/machine-learning/support-vector-regression-svr-using-linear-and-non-linear-kernels-in-scikit-learn/. 
