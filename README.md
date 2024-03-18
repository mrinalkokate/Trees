# Trees

<h2>Decision Tree Classifier<h2>
<sub>Decision Trees (DTs) are a non-parametric supervised learning method used for classification and regression. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features. A tree can be seen as a piecewise constant approximation.
The name itself suggests that it uses a flowchart like a tree structure to show the predictions that result from a series of feature-based splits. It starts with a root node and ends with a decision made by leaves.</sub>

<br />


<p align="center">
What it Looks Like: <br/>
<img src="https://i.imgur.com/krn0Puq.png" height="80%" width="80%" alt="Disk Sanitization Steps" />
<br />

<sub>The data preparation process involves several key steps:</sub>

  - <sub>Data Collection: Gather relevant data from various sources like operational systems, data warehouses, and data lakes. Ensure collected data aligns with the objectives of planned analytics applications.</sub>

  - <sub> Data Discovery and Profiling: Explore collected data to understand its content and requirements for preparation. Data profiling identifies patterns, relationships, inconsistencies, and missing values.</sub>

 - <sub> Data Cleansing: Correct identified data errors and issues to create complete and accurate datasets. Remove or fix faulty data, fill in missing values, and harmonize inconsistent entries.</sub>

 - <sub> Data Structuring: Model and organize data to meet analytics requirements. Convert data into structured formats like tables for accessibility to BI and analytics tools.</sub>

- <sub>  Data Transformation and Enrichment: Transform data into a unified and usable format. Create new fields or columns by aggregating values from existing ones. Enhance data through enrichment measures like augmenting and adding data.</sub>

- <sub> Data Validation and Publishing: Run automated routines to validate data consistency, completeness, and accuracy. Store prepared data in repositories like data warehouses or data lakes. Make it available for direct use or access by other users.</sub>

<p align="center">
Below is the code for Data Preparation in Python: <br/>
<img src="https://i.imgur.com/23Yw6dh.png" height="80%" width="80%" alt="Disk Sanitization Steps" />
<br />

<h2>Entropy</h2>
<sub>Entropy, in the context of information theory, is a measure of uncertainty or randomness associated with a random variable or a probability distribution. It quantifies the amount of disorder or unpredictability in a system. The concept of entropy originates from thermodynamics, where it represents the degree of disorder in a physical system.</sub>




<h2> SKLEARN </h2>
<sub>Scikit-learn (sklearn) is a Python library that provides simple and efficient tools for data mining, analysis, and machine learning, including algorithms for classification, regression, clustering, and dimensionality reduction.</sub>

<sub>
From SKLEARN import Tree:</sub>
<p align="center">
Using Decision Tree Classifier: <br/>
<img src="https://i.imgur.com/Pj49go3.png" height="80%" width="80%" alt="Disk Sanitization Steps" />
<br />

What is a Hyperparameter?

<sub>In machine learning, a hyperparameter is a configuration setting external to the model that cannot be learned from the data. Unlike model parameters, which are learned during training, hyperparameters are set prior to training and control aspects of the learning process. They are essential for tuning the behavior of the learning algorithm and optimizing the performance of the model.</sub>



GRIDSEARCH 
  
<sub>Grid search is a hyperparameter tuning technique used to systematically search for the optimal combination of hyperparameters for a machine learning model. Hyperparameters are parameters that are set before the learning process begins, such as the learning rate, regularization strength, or the number of hidden units in a neural network.</sub>

- <sub>For decision trees, hyperparameters may include the maximum depth of the tree, minimum samples required to split a node, minimum samples required at each leaf node, etc.
-  <sub>For Random Forests, hyperparameters may include the number of trees in the forest, maximum depth of each tree, minimum samples required to split a node, etc.</sub>
-  <sub>For Gradient Boosting Machines, hyperparameters may include the learning rate, maximum depth of the trees, number of trees, etc.</sub>

<p align="center">
Using Gridsearch: <br/>
<img src="https://i.imgur.com/wped3Z6.png" height="80%" width="80%" alt="Disk Sanitization Steps" />
<br />

<p align="center">
Using Gridsearch for Best Depth and Best Feature: <br/>
<img src="https://i.imgur.com/fLi8QPB.png" height="80%" width="80%" alt="Disk Sanitization Steps" />
<br />


<p align="center">
So we go on iterating with BEST Depth and Best Feature: <br/>
<img src="https://i.imgur.com/xKjZXn9.png" height="80%" width="80%" alt="Disk Sanitization Steps" />
<br />

<h2> Confusion Matrix </h2>
<sub>A confusion matrix is a table that is often used to describe the performance of a classification model (a model that predicts categorical outcomes). It compares the predicted labels of a model with the actual labels in the dataset.</sub>

<sub>Here's how it works:</sub>
<sub>Imagine you have a dataset with actual labels (e.g., "cat" or "dog") and predicted labels from your model.</sub>
<sub>The confusion matrix will have rows and columns representing the actual classes and predicted classes, respectively.Each cell in the matrix represents the count (or proportion) of instances where the predicted label matches the actual label for a specific class.</sub>

The four main components of a confusion matrix are:

- <sub>True Positives (TP): Instances where the model correctly predicts the positive class.</sub>
- <sub>True Negatives (TN): Instances where the model correctly predicts the negative class.</sub>
- <sub>False Positives (FP): Instances where the model incorrectly predicts the positive class (it predicts positive, but the actual label is negative).</sub>
- <sub>False Negatives (FN): Instances where the model incorrectly predicts the negative class (it predicts negative, but the actual label is positive).</sub>










