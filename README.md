Download Link: https://assignmentchef.com/product/solved-cse6363-project-2-ada-boost-and-bagging
<br>
<h1>Ensemble Classifiers</h1>

<ol>

 <li>Consider the problem where we want to predict whether a banknote is authentic or not from a set of realnumbered attributes characterizing properties of small image patches taken of the banknote, namely: i) the variance of the Wavelet transformed image, ii) the skewness of the Wavelet transformed image, iii) the curtosis of the Wavelet transformed image, and iv) the entropy of image.</li>

</ol>

There is a training and a test data set for this problem on Blackboard (datasets are derived from the more expansive UCI machine learning banknote data set and a re structured as comma separated lists with one data point per line where the first 4 numbers are the features and the final entry – 0 or 1 – indicates the class the data point belongs to ).

<ol>

 <li>Implement a bagging routine for a logistic regression classifier. You have to implement baggingyourself but can use an existing implementation of logistic regression.</li>

 <li>Apply bagging 10, 50, and 100 times to the training data. For each of the three cases, evaluate theresulting ensemble classifier on the test data set and compare the error rates for a single classifier and the three ensemble classifiers. Briefly discuss the results you obtained.</li>

</ol>

<ol start="2">

 <li>Using the data and logistic regression classifier, apply boosting to the problem.

  <ol>

   <li>Implement AdaBoost on top of your logistic regression classifier.</li>

   <li>Apply boosting 10, 25, and 50 times to the training data. For each of the three cases, evaluate theresulting ensemble classifier on the test data set and compare the error rates for a single classifier and the three ensemble classifiers. Briefly discuss the results you obtained.</li>

  </ol></li>

</ol>