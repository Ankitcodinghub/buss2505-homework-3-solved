# buss2505-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [BUSS2505 Homework 3 Solved](https://www.ankitcodinghub.com/product/buss2505-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;122105&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;BUSS2505 Homework 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
Machine Learning

Ham or Spam

After pre-processing the content of the emails, we have extracted 57 features from those emails.

Your task now is to build a spam filter to predict whether an email is a spam or not.

Data

In the dataset (see spambase.csv) provided by the client company, the first 48 columns indicate the feature word freq WORD, the percentage of words in the email that match WORD (number of times the WORD appears in the email/total number of words in email * 100). The following 6 columns indicates the feature char freq CHAR, the percentage of characters in the email that match CHAR. The next column indicates the feature capital run length longest, the length of longest uninterrupted sequence of capital letters. The last feature is capital run length total, the total number of capital letters in the email. The last three features have been standardized for improving the efficiency of training process of the models. The last column indicates whether the email was considered as spam (1) or not (0). There are in total 4600 instances in this dataset.

Programming assignment

In this assignment, you will implement Support Vector Machine on the spambase dataset to predict whether the email is spam or not using Python. You can either use the functions from libraries such as scikit-learn or write the code from scratch to implement the algorithm. After you run the sample code (see, “svm demo.py”) successfully (this step is not required, but recommended), you should apply the Support Vector Machine following the instructions as below. In this assignment, you should use linear kernels and set the penalty coefficient C to 1 if those parameters are not

specified.

1. Learn and apply the algorithm (20pts)

a. For each W in [10, 20, 30, 40, 50, 57]

i. Use the first W features and randomly sample 70% of the data for training and use the remaining 30% of the data for testing iii. Learn a model from the training data and apply it to test data iv. Measure the performance on both the training and test data using accuracy

v. Repeat 100 times with different random samples (using the same W) vi. Record and report the average and the standard deviation of accuracy on both training and test sets across the 100 trials

b. Plot curves for the results (the number of features vs avg., the number of features vs std. dev.) for both training and test data. Discuss the results.

2. Explore the effect of the penalty coefficient C (25pts)

a. Randomly sample 80% of the data for training and use the remaining 20% of data for

testing.

b. For each C in [0.001, 0.01, 0.1, 1, 10]

i. Use 10-fold cross validation on the training set to evaluate the accuracy of the SVM with the penalty coefficient C.

ii. Record and report the average and the standard deviation of accuracy on 10 validation sets.

iii. Record and report the average margin of the SVM that you trained.

c. Plot curves for the results (the penalty coefficient vs the avg. accuracy, the penalty coefficient vs the std. dev. of accuracy, the penalty coefficient vs the avg. margin). Discuss the results.

d. Choose a penalty coefficient C and give the reason why you choose this penalty coeffi-

cient.

e. Learn the SVM model on the whole training set with the chosen penalty coefficient C and report the accuracy on the testing set.

3. Comparison with Logistic Regression (15pts)

a. Evaluate the accuracy of SVM and Logisitc Regression using 10-fold cross validation on the whole dataset.

b. Record and report the average and the standard deviation of the accuracy of SVM and Logistic Regression on the validation sets.

c. Record and report the average precision and average recall of SVM and Logistic Regression on validation sets.

d. Is one classifier better than the other based on the performance metric accuracy? Use the paired t-test to justify your conclusion.

Hint

validation.

Submission

1. The source code in python.

this:

$python svm.py

The average accuracy with different penalty coefficients:

[0.111 0.333 0.777 0.212 0.676 ] The std. dev. of accuracy with different penalty coefficients:

[0.013 0.013 0.012 0.011 0.012]

The average margin with different penalty coefficients:

[1.432 2.212 0.266 3.154 1.089]

2. Your evaluation &amp; analysis in .pdf format.

Note that your analysis should include the graphs as well as a discussion of results.
