# CS585 - Winter Project

Movie Review Classification On Weka
===================================


Accuracy of Naive Bayes Classifier:
-----------------------------------

|                              | Actual Value      | Percent Value   |
|------------------------------|-------------------|-----------------|
|Correctly Classified Instances|        1590        |       79.5    %|
|Incorrectly Classified Instances|       410         |      20.5    %|
|Kappa statistic                  |        0.59  |                   
|Mean absolute error              |        0.2228|
|Root mean squared error          |        0.396 |
|Relative absolute error          |       44.5573 %|
|Root relative squared error      |       79.1907 %|
|Total Number of Instances        |     2000     |

Prediction using Naive Bayes Classifier
========================================

>Time taken to build model: 0.03 seconds

Predictions on test split
--------------------------


|inst#|    actual| predicted| error| probability| distribution|
|-----|----------|----------|------|------------|-------------|
|    1|          ?|      1:neg|      +|  *0.851  |0.149|
|     2|          ?|      1:neg|     +|  *0.987|  0.013|
|     3|          ?|      1:neg |     +|  *0.96   |0.04 |
|     4|          ?|      1:neg |     +|  *0.997 | 0.003|
|     5|          ?|      1:neg |     +|  *0.98  | 0.02|
|     6|          ?|      1:neg |     +|  *0.999 | 0.001|
|     7|          ?|      1:neg |     +|  *0.999 | 0.001|
|     8|          ?|      1:neg |     +|  *1     | 0    |
|     9|          ?|      2:pos |     +|   0.199 |*0.801|
|    10|          ?|      1:neg |     +|  *0.998 | 0.002|
|    11|          ?|      2:pos |     +|   0.033 |*0.967|
|    12|          ?|      1:neg |     +|  *0.73  | 0.27 |
|    13|          ?|      1:neg |     +|  *1     | 0    |
|    14|          ?|      1:neg |     +|  *1     | 0    |
|    15|          ?|      1:neg |     +|  *0.999 | 0.001|
|    16|          ?|      1:neg |     +|  *0.903 | 0.097|
|    17|          ?|      1:neg |     +|  *1     | 0    |
|    18|          ?|      1:neg |     +|  *0.999 | 0.001|
|    19|          ?|      2:pos |     +|   0.358 |*0.642|
|    20|          ?|      1:neg |     +|  *0.999 | 0.001|


Accuracy of the J48 Tree Classification mechanism
=================================================

|                               |  Actual Value | Percent Value        |
|-------------------------------|---------------|----------------------|
|Correctly Classified Instances        |1453|               72.65   %  |
|Incorrectly Classified Instances       |547 |              27.35   %  |
|Kappa statistic                          |0.453
|Mean absolute error                      |0.3368
|Root mean squared error                  |0.4553
|Relative absolute error                 |67.3626 %
|Root relative squared error            | 91.0551 %
|Total Number of Instances             |2000|



Predictions using J48 Tree Classifier
=====================================

>Time taken to build model: 0.48 seconds

Predictions on test split
---------------------------

|inst |   actual |predicted |error |probability| distribution |
|-----|----------|----------|------|-----------|--------------|
|     1|          ?|      1:neg|      +|  *0.78    |0.22  |
|     2|          ?|      1:neg|      +|  *0.866   |0.134 |
|     3|          ?|      1:neg|      +|  *0.884   |0.116 |
|     4|          ?|      1:neg|      +|  *0.78    |0.22 |
|     5|          ?|      1:neg|      +|  *0.775   |0.225|
|     6|          ?|      1:neg|      +|  *0.78    |0.22 |
|     7|          ?|      1:neg|      +|  *0.88    |0.12 |
|     8|          ?|      1:neg|      +|  *0.866   |0.134|
|     9|          ?|      2:pos|      +|   0.176   |*0.824|
|    10|          ?|      1:neg|      +|  *0.884   |0.116|
|    11|          ?|      2:pos|      +|   0.2     |*0.8  |
|    12|          ?|      1:neg|      +|  *0.667   |0.333|
|    13|          ?|      1:neg|      +|  *0.733   |0.267|
|    14|          ?|      1:neg|      +|  *0.972   |0.028|
|    15|          ?|      1:neg|      +|  *0.775   |0.225|
|    16|          ?|      1:neg|      +|  *0.86    |0.14 |
|    17|          ?|      1:neg|      +|  *0.876   |0.124|
|    18|          ?|      1:neg|      +|  *0.78    |0.22 |
|    19|          ?|      1:neg|      +|  *0.833   |0.167|
|    20|          ?|      1:neg|      +|  *0.86    |0.14 |




> Current progress of the project: Successfully able to predict the movie review with the given accuracy of the models from training and test data using weka.

** Working on Word2vec to create weka friendly models that can be used for Classification
