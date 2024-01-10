
To check for bias in an A/B test before the actual test, you typically want to compare the baseline characteristics of the control and treatment groups. You have the following data:

plaintext
Copy code
                      label  control  treatment
0      churn_before_release     9335      11974
1  non_churn_before_release    50592       8311
To assess bias, you can calculate proportions or percentages for each category within each group and compare them. Here's how you can do it:

Calculate the proportions for each category within the control group:

Proportion of "churn_before_release" in the control group: 
9335
9335
+
50592
9335+50592
9335
​
 
Proportion of "non_churn_before_release" in the control group: 
50592
9335
+
50592
9335+50592
50592
​
 
Calculate the proportions for each category within the treatment group:

Proportion of "churn_before_release" in the treatment group: 
11974
11974
+
8311
11974+8311
11974
​
 
Proportion of "non_
