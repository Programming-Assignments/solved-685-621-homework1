Download Link: https://assignmentchef.com/product/solved-685-621-homework1
<br>
Use induction to prove.

<h1>2.    Problem 2 Parts a, b, c, d, e and f</h1>

Although merge sort runs in Θ(<em>nlgn</em>) worst-case time and insertion sort runs in Θ(<em>n</em><sup>2</sup>) worst-case time, the constant factors in insertion sort can make it faster in practice for small problem sizes on many machines. Thus, it makes sense to coarsen the leaves of the recursion by using insertion sort within merge sort when subproblems become sufficiently small. Consider a modification to merge sort in which <em>n/k </em>sublists of length <em>k </em>are sorted using insertion sort and then merged using the standard merging mechanism, where <em>k </em>is a value to be determined.

<ul>

 <li>Use insertion sort to sort the unsorted array <em>&lt; </em>40<em>,</em>17<em>,</em>45<em>,</em>82<em>,</em>62<em>,</em>32<em>,</em>30<em>,</em>44<em>,</em>93<em>,</em>10 <em>&gt;</em>. Make sure to show the array after every pass.</li>

 <li>Use merge sort to sort the unsorted array <em>&lt; </em>75<em>,</em>56<em>,</em>85<em>,</em>90<em>,</em>49<em>,</em>26<em>,</em>12<em>,</em>48<em>,</em>40<em>,</em>47 <em>&gt;</em>. Make sure to show the steps of splitting the array then merging the array.</li>

 <li>Show that insertion sort can sort the <em>n/k </em>sublists, each of length <em>k</em>, in Θ(<em>nk</em>) worst-case time. <strong>(d) </strong>Show how to merge the sublists in Θ(<em>nlg</em>(<em>n/k</em>)) worst-case time.</li>

 <li>Given that the modified algorithm runs in Θ(<em>nk </em>+ <em>nlg</em>(<em>n/k</em>)) worst-case time, what is the largest value of <em>k </em>as a function of <em>n </em>for which the modified algorithm has the same running time</li>

</ul>

1

as standard merge sort, in terms of Θ-notation?

<ul>

 <li>How should we choose <em>k </em>in practice?</li>

</ul>

<h1>3.    Problem 3</h1>

Write a Θ(<em>m </em>+ <em>n</em>) algorithm that prints the in-degree and the out-degree of every vertex in an <em>m</em>-edge, <em>n</em>-vertex directed graph where the directed graph is represented using adjacency lists.

<h1>4.    Problem 4 Chapter 12 Binary Search Trees</h1>

<strong>Exercise 12.2-1</strong>. Suppose that we have numbers between 1 and 1000 in a binary search tree and we want to search for the number 363. Which of the following sequences could not be the sequence of nodes examined?

<ol start="363">

 <li>2, 252, 401, 398, 330, 397, 363.</li>

 <li>924, 220, 911, 244, 898, 258, 362, 363. 925, 202, 911, 240, 912, 245, 363.</li>

 <li>2, 399, 387, 219, 266, 382, 381, 278, 363.</li>

 <li>935, 278, 347, 621, 299, 392, 358, 363.</li>

 <li><strong>Problem 5 Sorting Iris Plants </strong><em>Note this is a Collaborative Problem</em></li>

</ol>

The Iris Plants Database contains 3 classes of 50 instances each, where each class refers to a type of Iris plant. Five attributes/features were collected for each plant instance. The dataset can be downloaded from <a href="https://storm.cis.fordham.edu/~gweiss/data-mining/datasets.html">iris.arff on the Sample Weka Data Sets webpage (https://storm.cis.fordham.edu/</a> gweiss/data<a href="https://storm.cis.fordham.edu/~gweiss/data-mining/datasets.html">mining/datasets.html).</a> Develop an algorithm to sort the five features in the dataset to determine if any of the five sorted features can separate the three plant types. Show the efficiency of your sorting algorithm based on its ability to sort the five sets of features.