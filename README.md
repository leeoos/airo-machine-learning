# AIRO Machine Learning
Machine Learning Homeworks - Sapienza (AIRO) 2022/2023

## How to test the code 
To test the code simply open the python notebook called `model.ipynb` inside the directory *code* in [Google Colab](https://colab.research.google.com/).

Before running the code on Colab make sure to download the data-set inside *dataset* and import it under 
 
## Assignment
The goal of the homework is to make predictions and risk analysis over a set of data. The data-set provided for the assignment is a tab separated file (tsv ) containing information about 5 different UAV. The information, organized as 7 columns for each drone for a total of 35 features, describes a set of UAVs positions and velocities, them orientations with respect to some targets and the targets positions. Additionally there are two output columns for two different problems of classification and regression. The first output column contains integer values, from zero to four, which are the labels for the classification problem, and represent the number of collisions between the 5 drones. The second column contains real values, the output for the regression problem, which represents the min-CPA between all the pairs of drones. CPA or Closest Point of Approach is an estimated point in which the distance between two objects, of which at least one is in motion, will reach its minimum value.As one aspect of the assignment was to operate in a domain independent way, all this information are useful to describe the problems to be solved but are not actually relevant for the solution itself. In fact all the given data has been treated just as numbers during the implementation of the ML algorithms. The specific goal of the homework is discussed in the next sub-sectionwhich also describes the limitations of the data-set.
