# machinelearning-assignment--decision-tree-solved
**TO GET THIS SOLUTION VISIT:** [MachineLearning Assignment -Decision Tree Solved](https://www.ankitcodinghub.com/product/machinelearning-assignment-decision-tree-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96016&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MachineLearning Assignment -Decision Tree Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

1 Overview

In this assignment, you will implement a decision tree algorithm and use it to determine one of the indoor locations based on WIFI signal strengths collected from a mobile phone. See Figure 1 for an illustration of the experimental sce- nario. The results of your experiments should be discussed in the report. You should also deliver the code you have written.

Deadline: Fri – 06 Nov 2020 (7pm) on CATE

2 Setup

We do recommend you work on the Ubuntu workstations in the lab. This assignment and all code were tested for Linux and Mac OS machines. We cannot guarantee compatibility with Windows machine and cannot promise any support if you do choose to work on a Windows machine.

2.1 Working on DoC lab workstations (recommended)

You can also work from home and use the lab workstations. See this list of https://www.doc.ic.ac.uk/csg/facilities/lab/workstations to ssh into one of the machines.

In order to load all the packages that you might need for the course work, you can run the following command:

<pre>export PYTHONUSERBASE=/vol/lab/ml/mlenv
</pre>
We installed numpy, matplotlib, pytorch, which should cover most of the packages you will need for all the courseworks in this course. If you don’t want to type that command every time that you connect to your lab machine, you can add it to your bashrc:

<pre>echo "export PYTHONUSERBASE=/vol/lab/ml/mlenv" &gt;&gt; ~/.bashrc
</pre>
This way, every terminal you open will have that environment variable set. It is recommended to use ”python3” exclusively. The current python3 version in lab machines is 3.8.5. To test the configuration:

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Room 1

Room 4

</div>
<div class="column">
Room 2

Room 3

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: Illustration of the scenario. The WIFI signal strength from 7 emitters are recorded from a mobile phone. The objective of this coursework is to learn decision tree that predict in which of the 4 rooms the user is standing.

python3 -c “import numpy as np; print(np)” This should print:

&lt;module ‘numpy’ from ‘/vol/lab/ml/mlenv/lib/python3.8/site-packages/numpy/__init__.py’&gt; 2.2 Working on your own system

If you decide to work locally on your machine, then you will need to give us explicit instructions how to run your code. Anything we cannot run will result to your points of the question reduced by 30%.

Python&gt;= 3.5: All provided code has been tested on Python versions 3.5 or 3.6. Make sure to install Python version 3.5 or 3.6 on your local machine. Otherwise, you might encounter errors! If you are working on Mac OSX, you can use Homebrew to brew install python3.

2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Part 1: Implementation Step 1: Loading data

You can load the datasets from the files ”WIFI db/clean dataset.txt” and ”WIFI db/noisy dataset.txt”. They contain a 2000×8 array. This array repre- sents a dataset of 2000 samples. Each sample is composed of 7 WIFI signal strength while the last column indicates the room number in which the user is standing (i.e., the label of the sample). All the features in the dataset are continuous except the room number. You can load the text file with the ”loadtxt” function from Numpy. Given the nature of the dataset you will have to build decision trees capable of dealing with continuous attributes and multiple labels.

Step 2: Creating Decision Trees

To create the decision tree, you will write a recursive function called deci- sion tree learning(), that takes as arguments a matrix containing the dataset and a depth variable (which is used to compute the maximal depth of the tree, for plotting purposes for instance). The label of the training dataset is as- sumed to be the last column of the matrix. The pseudo-code of this function is described below. This pseudo-code is taken from Artificial Intelligence: A Mod- ern Approach by Stuart Russell and Peter Norvig (Figure 18.5), but modified to take into account that the considered dataset contains continuous attributes (see section 18.3.6 of the book).

Algorithm 1 Decision Tree creating

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 2: 3: 4: 5: 6: 7: 8: 9:

10: 11:

</div>
<div class="column">
procedure decision tree learning(training dataset, depth) if all samples have the same label then

return (a leaf node with this value, depth) else

split← find split(training dataset)

node← a new decision tree with root as split value

l branch, l depth ← DECISION TREE LEARNING(l dataset, depth+1) r branch, r depth ← DECISION TREE LEARNING(r dataset, depth+1) return (node, max(l depth, r depth))

end if

end procedure

</div>
</div>
<div class="layoutArea">
<div class="column">
The function FIND SPLIT chooses the attribute and the value that results in the highest information gain. Because the dataset has continuous attributes, the decision-tree learning algorithms search for the split point (defined by an attribute and a value) that gives the highest information gain. For instance, if you have two attributes (A0 and A1) with values that both range from 0 to 10, the algorithm might determine that splitting the dataset according to ”A1&gt;4” gives the most information. An efficient method for finding good split points is

3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
to sort the values of the attribute, and then consider only split points that are between two examples in sorted order, while keeping track of the running totals of positive and negative examples on each side of the split point.

To evaluate the information gain, suppose that the training dataset Sall has K different labels. We can define two subsets (Sleft and Sright) of the dataset depending on the splitting rule (for instance ”A1&gt;4”) and for each dataset and subset, we can compute the distribution (or probability) of each label. For instance, {p1p2 . . . pK } (pk is the number of samples with the label k divided by the total number of samples from the initial dataset). The information gain is defined by using the general definition of the entropy as follow:

Gain(Sall, Sleft, Sright) = H(Sall) − Remainder(Sleft, Sright)

k=K

H(dataset) = − 􏰀 pk ∗ log2(pk)

k=1

Remainder(Sleft,Sright) = |Sleft| H(Sleft)+ |Sright| H(Sright) |Sleft| + |Sright| |Sleft| + |Sright|

Where |S| represents the number of samples in subset S. Implementation:

You are only allowed to use Numpy and Matplotlib for this course- work. Any other library, like scikit learn is NOT allowed. For the implementation of the tree (in Python), it is advised to use dictionaries to store nodes as a single object, for instance by using this kind of structure {’attribute’, ’value’, ’left’, ’right’}. In this case, ’left’ and ’right’ will also be nodes. You might also want to add a Boolean field name ”leaf” that indicates whether or not the node is a leaf (terminal node) or not. However, this is not strictly necessary, as there are other methods to determine if a node is terminal or not.

Bonus (5 points): Write a function to visualize the tree. See Figure 2 for an example. You can only use Numpy and Matplotlib for this question as well.

Step 3: Evaluation

Now that you have an automatic process to train decision trees, you can evaluate the accuracy of your tree on the provided datasets. For that, evaluate your decision tree using 10-fold cross validation on both the clean and noisy datasets. You should expect that slightly different trees will be created per each fold, since the training data that you use each time will be slightly different. Use your resulting decision tree to classify your data in your test set.

4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Figure 2: example of Decision tree visualization (not all the tree is displayed, and this tree has been trained on a different dataset.)

Implementation:

Implement an evaluation function that takes a trained tree and a test dataset: evaluate(test db, trained tree) and that returns the accuracy of the tree.

Write report the average cross validation classification results (for both clean and noisy data):

<ul>
<li>Confusion matrix. (Hint: you should get a single 4×4 matrix)</li>
<li>Average recall and precision rates per class. (Hint: you can derive themdirectly from the previously computed confusion matrix)</li>
<li>TheF1-measuresderivedfromtherecallandprecisionratesoftheprevious step.</li>
<li>Average classification rate (NOTE: classification rate = 1 – classification error).Comment on the results of both datasets, e.g. which rooms are recognized with high/low accuracy, which rooms are confused.
Step 4: Pruning (and evaluation again)

In order to reduce the performance difference of our decision tree between the clean and noisy dataset, you will implement a pruning function based on reduc- ing the validation error. This approach works as follow: for each node directly connected to two leaves, evaluate the benefits on the validation error of substi- tuting this node with a single leaf (defined according to the training set). If a single leaf reduces the validation error, then the node in pruned and replaced by a single leaf. The tree needs to be parsed several times until there is no more

5
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
node connected to two leaves (HINT: when you prune a node, the parent node might now verify this condition).

Compare the performances of your tree before and after pruning on a 10-fold cross validation and comment in your report.

Part 2: Questions

Answer to the following questions in your report:

Noisy-Clean Datasets Question Is there any difference in the performance when using the clean and noisy datasets? If yes/no explain why. Discuss the differences in the overall performance and per class.

Pruning Question Briefly explain how you implemented your pruning func- tion and details the influence of the pruning on the accuracy of your tree on both datasets.

Depth Question Comment on the maximal depth of the tree that you gen- erated for both datasets and before and after pruning. What can you tell about the relationship between maximal depth and prediction accuracy?

Part 3: Deliverables

For the completion of this part of the coursework, the following has to be sub- mitted electronically via CATE:

• All the code you have written

• A README file (in txt) to explain how to run your code.

• A report of approximately 4-5 pages (excluding figures and tables) con- taining the following:

<ul>
<li>– &nbsp;Brief summary of implementation details (e.g., how you performed cross-validation, how you selected the best attribute in each node, how you compute the average results, anything that you think it is important in your system implementation);</li>
<li>– &nbsp;Commented results of the evaluation including the average confusion matrix, the average classification rate and the average precision, re- call rates and F1-measure for each of the four classes; for both clean and noisy datasets.</li>
<li>– &nbsp;Diagrams of the trees trained on the entire dataset (bonus points)</li>
<li>– &nbsp;Answers to the three questions of Part 2.6</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
