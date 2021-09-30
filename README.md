# SDS Mentorship Program Task
Task 1 - Build a decision Tree model

## Balance Scale Data Set
Decision Tree Model on balance data from UCI -> [Dataset](https://archive.ics.uci.edu/ml/datasets/Balance+Scale)

## Project Submission Guidelines: 
<b>Don't use Github GUI at all, do all work in CLI mode (except for making Pull Request)</b>

1. First Fork the Repo.
2. Then go to issue section of my repo.
3. Search the Issue with your name.
4. Ask me in Comments to assign the issue to you.
5. After that you can clone the repo of yours in your local system ```git clone https://Your/Repo/Name/```
6. Then make a dev branch using -> ``` git checkout -b dev``` 
7. Upload the project in folder according to name.
8. Your project files should contain a .gitignore file <I>(So that you don't have to upload redundant files like '.ipynb_checkpoints',etc)</I>. 
9. Update the the readme files of your project folder
10. then add ```git add .``` and commit ```git commit -m "add project files" ``` all your work 
11. to your origin/dev branch using -> ```git push -u origin dev```
12. And then finally make A Pull Request <I>(from your dev branch to my main branch)</I> by going to your github forked repo.
13. Write a suitable title and comment in your Pull Request(PR).
14. If Everything will be fine It'll get merge.

## Dataset Description
1. **Title:** Balance Scale Weight & Distance Database

2. **Source Information:**
    (a) **Source:** Generated to model psychological experiments reported
		by Siegler, R. S. (1976).  Three Aspects of Cognitive
		Development.  Cognitive Psychology, 8, 481-520.
    (b) **Donor:** Tim Hume (hume@ics.uci.edu)
    (c) **Date:** 22 April 1994

3. **Relevant Information:**
	This data set was generated to model psychological
	experimental results.  Each example is classified as having the
	balance scale tip to the right, tip to the left, or be
	balanced.  The attributes are the left weight, the left
	distance, the right weight, and the right distance.  The
	correct way to find the class is the greater of 
	(left-distance * left-weight) and (right-distance *
	right-weight).  If they are equal, it is balanced.
  
	| Data Set Characteristics: | Multivariate | Number of Instances: | 625 | Area: | Social |
	| :---: | :---: | :---: | :---: | :---: | :---: |
	| Attribute Characteristics: | Categorical | Number of Attributes: | 4 | Date Donated: | 1994-04-22 |
	| Associated Tasks: | Classification | Missing Values? | No | Number of Web Hits: | 291160 |
  
4. **Number of Instances:** 625 (49 balanced, 288 left, 288 right)

5. **Number of Attributes:** 4 (numeric) + class name = 5

6. **Attribute Information:**
	1. Class Name: 3 (L, B, R)
	2. Left-Weight: 5 (1, 2, 3, 4, 5)
	3. Left-Distance: 5 (1, 2, 3, 4, 5)
	4. Right-Weight: 5 (1, 2, 3, 4, 5)
	5. Right-Distance: 5 (1, 2, 3, 4, 5)

7. **Class Distribution:**
   1. 46.08 percent are L
   2. 07.84 percent are B
   3. 46.08 percent are R
