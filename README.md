# Fake_Currency_Detection

This machine learning task consists of binary classification of bank notes to determine whether or not they are real.  
As someone who currently works at a bank, being able to tell whether a bill is fake or not is integral to my work.  
At one point, I wondered if it was possible for a machine learning algorithm to determine if bills were fake or not.
And it was!  Using this dataset, the bills had four characteristics, being:

1. The variance of the image
2. The asymmetry of the image
3. Image Kurtosis
4. Image entropy

Using logistic regression, we can determine whether or not a bill is fake using the parameters mentioned above.  